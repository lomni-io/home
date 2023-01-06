<template>
  <div class="hello">

    <div class="logo">
      <div class="logo-container">
        <div class="logo-l">L</div>
        <div class="logo-omni">omni</div>
      </div>
    </div>

    <p class="subtitle">
      Or you can call it <strong>Linked Omnni</strong>
    </p>

    <div class="divider"></div>

    <p>
      Lomni is a easy way to organize and search easily all your <a>#links</a> using chrome sidebar.

    </p>

    <p>
      Lomni uses a powerful <a>#tags</a> search logic engine to help you to add tags and find it easily.
    </p>

    <h2>How to set up Lomni</h2>

    <ul>
      <li><span class="li-item">1. </span>Install Lomni <a href="https://chrome.google.com/webstore/detail/lomni-sibebar/aekckpbdaninhmbbajcpedhaidaeofdh">chrome plugin</a></li>
      <li><span class="li-item">2. </span>open <a>chrome://flags/#side-panel-web-view</a> and enable the current flag</li>
      <li><span class="li-item">3. </span>now you can open the link <a>https://lomni-io.github.io/sidebar/latest/</a> in your webview sidebar. It's ready to use</li>
    </ul>


  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Satisfy&display=swap');

.logo{
  display: flex;
  justify-content: center;
}
.logo-container{
  display: flex;
}
.logo-l{
  font-size: 4em;
  font-family: 'Satisfy', cursive;
  background-color: var(--logo_l_background);
  text-align: center;
  width: 1.5em;
  border-radius: 10px;
  color: var(--logo_l_color);
}
.logo-omni{
  margin-left: -0.5em;
  font-size: 4em;
  color: var(--logo_omni_color);
}

.subtitle{
 text-align: center;
  font-style: italic;
}

.divider{
  border-bottom: 1px solid var(--text_color);
  margin-top: 2em;
  margin-bottom: 2em;
}

.p-center{
  text-align: center;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  margin: 0 10px;
}

.li-item{
  font-weight: bold;
  min-width: 20px;
  border-radius: 10px;
  font-size: 1.2em;
}

mark{
  background-color: transparent;
  color: var(--yellow);
}

a {
  color: var(--green);
}
</style>
