<template>
<div>

  <b-navbar toggleable>

    <b-nav-toggle target="nav_collapse" />

    <a class="navbar-brand" to="/">
      <span>{{title}}</span>
    </a>

    <b-collapse isNav id="nav_collapse" class="float-right">
      <b-nav isNavBar>
        <b-nav-item>已有案例</b-nav-item>
        <b-nav-item>关于我们</b-nav-item>
        <b-nav-item>联系我们</b-nav-item>
      </b-nav>
    </b-collapse>

  </b-navbar>
</div>
</template>

<script>
export default {
  name: 'top',
  data: () => {
    return {
      title: '千人行工作室'
    }
  }
}
</script>
