<template>
    <div class="content">
        <div class="card">
            <h2>Producto 1</h2>
            <p>Descripcion del producto 1</p>
            <button class="button">
                Comprar
            </button>
        </div>
        <div class="card">
            <h2>Producto 2</h2>
            <p>Descripcion del producto 2</p>
            <button class="button">
                Comprar
            </button>
        </div>
        <div class="card">
            <h2>Producto 3</h2>
            <p>Descripcion del producto 3</p>
            <button class="button">
                Comprar
            </button>
        </div>
    </div>
</template>

<style>
.button{
    background-color: rgb(1, 121, 255);
    color: white;
    padding: 10px;
    align-content: center;
    border-radius: 10px;
    border: none;
}

.content{
    width: 100%;
}

.card{
    display: inline-block;
    align-content: center;
    align-items: center;
    width: 250px;
    border: 0.5px solid grey;
    border-radius: 5%;
    margin: 10px;
    padding: 10px;
}

@media screen and (max-width: 768px) {
   .button{
    background-color: rgb(1, 121, 255);
    color: white;
    padding: 12px;
    align-content: center;
    border-radius: 10px;
    border: none;
    font-size: 15px;
}

.content{
    width: 100%;
}

.card{
    display: inline-block;
    align-content: center;
    align-items: center;
    width: 180px;
    border: 0.5px solid grey;
    border-radius: 5%;
    margin: 10px;
    padding: 10px;
} 
}

@media screen and (max-width: 425px) {
   .button{
    background-color: rgb(1, 121, 255);
    color: white;
    padding: 12px;
    align-content: center;
    border-radius: 10px;
    border: none;
    font-size: 15px;
}

.content{
    width: 100%;
}

.card{
    display: block;
    align-content: center;
    align-items: center;
    width: 350px;
    border: 0.5px solid grey;
    border-radius: 3%;
    margin: 15px;
    padding: 10px;
} 
}
</style>


