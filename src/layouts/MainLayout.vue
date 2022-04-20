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
        <q-btn-dropdown unelevated label="Dropdown Button" style="position:relative">
          <option value="345076">HIGH</option>
          <option value="345076">HIGH</option>
          <option value="345076">HIGH</option>
          <option value="345076">HIGH</option>
        </q-btn-dropdown>
        <q-btn-dropdown unelevated label="Dropdown Button">
          <option value="345076">HIGH</option>
          <option value="345076">HIGH</option>
          <option value="345076">HIGH</option>
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

    <q-footer elevated class="bg-grey-8 text-white">
      <q-toolbar>
        <q-toolbar-title>
          <q-avatar>
            <img src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-white.svg">
          </q-avatar>
          <div>Title</div>
        </q-toolbar-title>
      </q-toolbar>
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
