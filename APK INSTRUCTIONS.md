Use Bubblewrap as follows:

> pnpm i -g @bubblewrap/cli
>
> mkdir android
>
> cd android
>
> bubblewrap init --manifest https://scout.team4096.org/manifest.json
>
> Keystore password: 40964096
>
> COMMENT OUT "org.gradle.jvmargs=-Xmx1536m" in gradle.properties!
>
> bubblewrap build
