<template>
  <div class="main">
    <div class="card">
      <h1>About</h1>
      <p>
        Founded in 2020, Feather was created to provide modders with an open
        and intuitive platform to publish their projects on.
      </p>

      <p>
        Our primary goal is to be as open as possible, with all our code being
        <a target="_blank" href="https://github.com/gabrielvicenteYT">open source</a>,
        while giving back to the modding community as much as possible.
      </p>

      <p>
        While we still are in beta, we hope we can be a major modding platform
        for all modders.
      </p>
      <h2>How does Feather work?</h2>
      <p>
        Feather is not just a website: it is made of several different
        components that all come together to make a fast and flexible modding
        platform.
      </p>

      <p>
        On the technical level, Feather is made up of two main components: the
        Rust-based backend named
        <a target="_blank" href="https://github.com/gabrielvicenteYT/Feather-Mod-API"
          >Feather API</a
        >, and the Vue-based frontend named
        <a target="_blank" href="https://github.com/gabrielvicenteYT/Feather-Mod">Feather</a
        >.
      </p>

      <p>
        Additionally, some other custom-created resources exist, including but
        not limited to:
        <a target="_blank" href="https://github.com/modrinth/minotaur"
          >Minotaur</a
        >, a Gradle plugin for easily publishing mods to Feather, and
        <a target="_blank" href="https://github.com/gabrielvicenteYT/Feather-Mod-Auth">feather-auth</a>,
        an authentication provider. All of Feather's code can be found on
        <a target="_blank" href="https://github.com/gabrielvicenteYT">our GitHub page</a
        >.
      </p>
      <h2>Backend Documentation</h2>
      <p>
        Documentation for the Feathr API (feather-api) can be found on the GitHub
        repository's wiki
        <a target="_blank" href="https://docs.modrinth.com">here</a>.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  auth: false,
  head: {
    title: 'About - Feather',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content:
          'View information about Feather an open source modding platform here! Feather currently supports Minecraft, including the forge and fabric mod loaders.',
      },
      {
        hid: 'apple-mobile-web-app-title',
        name: 'apple-mobile-web-app-title',
        content: 'About',
      },
      {
        hid: 'og:title',
        name: 'og:title',
        content: 'About',
      },
      {
        hid: 'og:url',
        name: 'og:url',
        content: `https://feather-mod.vercel.app/about`,
      },
    ],
  },
}
</script>

<style lang="scss" scoped>
.main {
  margin: var(--spacing-card-sm) auto;
  max-width: 800px;
}

a {
  text-decoration: underline;
  color: var(--color-link);
}
</style>
