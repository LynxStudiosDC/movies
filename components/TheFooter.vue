<template>
  <footer p="y15 x15" flex="~ col gap4">
    <div flex="~ row gap2" items-center my2>
      <img src="/cloud.png" width="25" height="25" alt="Logo">
      <div text-xl>
        CloudFlix Movies
      </div>
    </div>
    <div flex="~ row gap2" items-center>
      <div op50 text-sm>
        Made with
      </div>
      <a href="https://lynxstudios.xyz" target="_blank" title="LynxStudios">
        <p>Lynx Studios</p>
      </a>
    </div>
    <div flex="~ row gap2" items-center>
      <p text-true-gray:90 text-sm>
        Data provided by&nbsp;
        <a op100 target="_blank" href="https://www.themoviedb.org/" title="The Movie Database" rel="noopener" n-link-text>
          <IconTMDB inline h4 />
        </a>
      </p>
    </div>
    <div flex="~ row gap2" items-center>
      <p text-true-gray:90 text-sm>
        This project uses the TMDB API but is not endorsed or certified by TMDB.
      </p>
    </div>
    <div flex gap4 items-center>
      <ExternalLinks
        :links="{
          twitter_id: '',
          github_id: '',
        }"
      >
          <p>&copy; 2024 CloudFlix. All rights reserved.</p>
        <a href="https://vercel.com" rel="noopener" target="_blank" aria-label="go to vercel">
          <IconVercel alt="Vercel" />
        </a>
      </ExternalLinks>

      <LanguageSwitcher />
    </div>
  </footer>
</template>
