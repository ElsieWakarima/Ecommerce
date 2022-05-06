<template>
    <h1>Items</h1>
    <div class="cartone">
        <img class="head" src="@/components/img/headphones1.jpg" alt="head">
        <p>Item1</p><button>Order</button>
    </div>
    <div class="cartone">
        <img class="head" src="@/components/img/headphones2.jpg" alt="head">
        <p>Item2</p><button>Order</button>
    </div>
    <div class="cartone">
        <img class="head" src="@/components/img/laptop1.jpg" alt="head">
        <p>Item3</p><button>Order</button>
    </div>
    <div class="cartone">
        <img class="head" src="@/components/img/watch1.jpg" alt="head">
        <p>Item4</p><button>Order</button>
    </div>
</template>
<style>
.cartone{
 box-shadow: 14px 14px 20px #5e73af, -14px -14px 20px rgb(8, 3, 3);
  padding: 5px 50px 15px 50px;
  margin: 50px;
  min-height: 100px;
  border-radius:25px;
}
p{
    float:left;
    padding-top:20px;
}
button{
    float:right;
    margin-top:20px;
    font-size:15px;
    width:10%;
    height:10%;
    cursor:pointer;
    border-radius:20px;

}
button:hover{
    background:rgba(102, 102, 161);

}
.head{
    width:100px;
    float:left;
    padding-top:20px;
    border:2px solid rgb(83, 83, 100)
}
@media (max-width: 720px) {
    button{
        width:50%;
    }
}

</style>
