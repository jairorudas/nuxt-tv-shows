<template>
  <nav class="w-screen flex justify-between">
    <ul>
      <li>
        <NuxtLink to="/" tag="el-link" type="primary">
          <img src="@/static/netflix-logo.png" class="w-[92px]" />
        </NuxtLink>
      </li>
      <li>
        <NuxtLink to="/" tag="el-link" type="primary"> Inicio </NuxtLink>
      </li>
      <li>
        <NuxtLink to="/series" tag="el-link" type="primary"> Séries </NuxtLink>
      </li>
      <li>
        <NuxtLink to="/filmes" tag="el-link" type="primary">
          Películas
        </NuxtLink>
      </li>
      <li>
        <NuxtLink to="/tranding" tag="el-link" type="primary">
          Mas vistos
        </NuxtLink>
      </li>
      <li>
        <NuxtLink to="/tranding" tag="el-link" type="primary">
          Mi Lista
        </NuxtLink>
      </li>
    </ul>
    <ul>
      <li>
        <NuxtLink to="/" tag="el-link" type="primary">
          <i class="el-icon-search text-lg hover:list-none"></i>
        </NuxtLink>
      </li>
      <li>
        <NuxtLink to="/" tag="el-link" type="primary"> Infantil </NuxtLink>
      </li>
      <li>
        <NuxtLink to="/" tag="el-link" type="primary">
          <el-badge value="1" class="item">
            <i class="el-icon-bell text-lg"></i>
          </el-badge>
        </NuxtLink>
      </li>
      <li>
        <NuxtLink to="/" tag="el-link" type="primary">
          <span
            class="flex content-center place-content-center place-items-center"
          >
            <el-avatar
              shape="square"
              size="small"
              src="https://randomuser.me/api/portraits/women/44.jpg"
            />
            <i class="el-icon-arrow-down !ml-4" />
          </span>
        </NuxtLink>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'NavBar',
}
</script>
<style lang="postcss">
nav {
  background-color: #0c0c0c;
}
ul {
  @apply p-3 inline-block;
  & li {
    @apply p-3 list-none inline-block !text-white;
    & a {
      @apply !text-white;
    }
  }
}
.el-badge__content {
  @apply !border-none;
}
</style>
