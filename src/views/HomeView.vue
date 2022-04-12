<template>
  <div class="home">
   <div class="header">
     <h2 class = "title">Hi <b>Vadim!</b></h2>
     <div class="input">
       <input type="text" placeholder="Find what you want...">
          <div class="icon-input">
              <i class='bx bx-search'></i>
          </div>
        </div>
      <div class= "combo-header">
            <div class="text">
              <h3><b>Free combo</b></h3>
              <p>Burguer + Coca-Cola for new users</p>
            </div>
            <div class="img">
              <img src="img\icons\hamburguesa.png">
            </div>
      </div>
   </div>
  </div>
</template>

<style lang="less">

  .home{
    margin: 20px;
  }
  .header{
    .combo-header{
      background-color: rgb(74, 174, 84);
      color: white;
      padding: 10px;
      border-radius: 20px;
      display:flex;
      justify-content: space-between;
      align-items: center;
      .img{
        width: 50%;
        margin-left: auto;
        img{
          width: 100%;
          object-fit: cover;
          border-radius: 10px;
          margin-left: 10px;
        }
      }
      .text{
        width: 50%;
        h3{
        font-weight: 400;
        }
        p{
          font-weight: 300;
        }
      }
    }
    .input{
      display: flex;
      width: 100%;
      align-items: center;
      margin-top: 12px;
      position: relative;
      input{
        width: 100%;
        background-color: rgb(248, 248, 248);
        border: 0ch;
        outline: none;
        padding: 10px;
        padding-left: 30px;
        border-radius: 10px;
      }
      .icon-input{
        position: absolute;
        margin-left: 10px;
        margin-top: 2px;
      }
    }
    .title{
      font-weight: 350;
    }
  }
</style>