<template>
  <nav class="mt-6">
    <ul class="list-disc">
      <li>
        <NavBarLink href="/" :active="$page.component == 'Welcome'">Welcome </NavBarLink>
      </li>
      <li>
        <NavBarLink href="/home" :active="$page.component == 'Home'"> Home </NavBarLink>
      </li>
    </ul>
  </nav>
</template>

<script>
import NavBarLink from "./NavBarLink.vue";
export default {
  components: { NavBarLink },
};
</script>
