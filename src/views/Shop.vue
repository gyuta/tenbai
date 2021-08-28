<template>
  <div>
  <div id="shop-name">ようこそ、〇〇ショップさん</div>

  <div id="cart">
    <div class="product">
      <div class="name">
        <div class="select">
          <select>
            <option>商品名を選択</option>
            <option>PS5</option>
            <option>靴</option>
            <option>〇〇のチケット</option>
          </select>
        </div>
      </div>
      <div class="num">
        <input class="input" type="number" placeholder="個数" value="1">
      </div>
    </div>
    <button class="button">商品を追加</button>
  </div>

    <div id="b-form">
      <div class="field is-grouped">
        <p class="control is-expanded">
          <input class="input" type="text" placeholder="ユーザー名を入力">
        </p>
      </div>
        <p class="control">
          <a class="button is-info">
            チェックする
          </a>
        </p>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang='scss'>
#shop-name {
  width: 100%;
  text-align: left;
} 
#b-form {
  padding: 30px;
}

.product {
  display: flex;
  padding: 50px;
  background-color: rgb(139, 136, 136);

  .name {
    width: 70%;
  }

  .num {
    .input {
      width: 50px;
    }
  }
}

</style>