<template>
  <q-layout view="hHh lpR fFf">
    <q-header bordered class="bg-transparent text-white" style="position: absolute" >
      <q-toolbar>
        <q-toolbar-title>
          <div class="text-h3" style="margin-left:40px;">
          <span>
            street
          </span>
          </div>
        </q-toolbar-title>
        <div class="row no-wrap justify-center items-center content-center" style="width:85%; bacground-color:transparent; height:100px;">
        <q-btn-dropdown unelevated label="Home" to="/index" style="position:relative">
        </q-btn-dropdown>
        <q-btn-dropdown unelevated label="Pages" class="column">
          <div class="column">
            <q-btn to="/about"> About Us</q-btn>
            <q-btn to="/ourwiew">Our Wiew</q-btn>
          </div>
        </q-btn-dropdown>
        <q-btn-dropdown unelevated label="Dropdown Button"></q-btn-dropdown>
        <q-btn-dropdown unelevated label="Dropdown Button"></q-btn-dropdown>
        <q-btn-dropdown unelevated label="Dropdown Button"></q-btn-dropdown>
        <q-btn-dropdown unelevated label="Dropdown Button"></q-btn-dropdown>
        <q-btn-dropdown unelevated label="Dropdown Button"></q-btn-dropdown>
        </div>
        <div>
        <q-btn flat round color="white" icon="" />
        </div>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer elevated class="bg-transparent text-black" style="heigth:100px">
      <!-- <q-toolbar>
        <q-toolbar-title>
          <q-avatar>
            <img src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-white.svg">
          </q-avatar>
          <div></div>
        </q-toolbar-title>
      </q-toolbar> -->
    <span style="margin-top:30px;margin-left:100px">© STREET. All Right Reserved 2022.</span>
    <q-icon name="telegram" style="margin-left:1000px;width:20px;height:20px"></q-icon>
    <q-icon name="facebook"></q-icon>
    <q-icon name="tweet"></q-icon>
    </q-footer>

  </q-layout>
</template>


<script>

export default ({

})
</script>
<style scoped>
  .q-toolbar{
    position: absolute;
  }
</style>
