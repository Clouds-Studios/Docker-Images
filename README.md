# Yolks

A curated collection of core images originally created by Matthew Penner, which can be used with Pterodactyl's Egg system. Each image is rebuilt
periodically to ensure dependencies are always up-to-date. 
These images have been modified to create a `libc.so` symlink for compatibility with Clouds Studios products.

Images are hosted on `ghcr.io` and exist under the `java` space. 
Since Clouds Studios products rely solely on Java 11+, we have modified only the Java 11+ Docker images and removed all others.

All of these images are available only for `linux/amd64`.

## Contributing

When adding a new version to an existing image, such as `java v42`, you'd add it within a child folder of `java`, so
`java/42/Dockerfile` for example. Please also update the correct `.github/workflows` file to ensure that this new version
is tagged correctly.

## Available Images

* [`java`](https://github.com/Clouds-Studios/Docker-Images/tree/master/java)
  * [`java11`](https://github.com/Clouds-Studios/Docker-Images/tree/master/java/11)
    * `ghcr.io/pterodactyl/yolks:java_11`
  * [`java11 - OpenJ9`](https://github.com/Clouds-Studios/Docker-Images/tree/master/java/11j9)
    * `ghcr.io/pterodactyl/yolks:java_11j9`
  * [`java16`](https://github.com/Clouds-Studios/Docker-Images/tree/master/java/16)
    * `ghcr.io/pterodactyl/yolks:java_16`
  * [`java16 - OpenJ9`](https://github.com/Clouds-Studios/Docker-Images/tree/master/java/16j9)
    * `ghcr.io/pterodactyl/yolks:java_16j9`
  * [`java17`](https://github.com/Clouds-Studios/Docker-Images/tree/master/java/17)
    * `ghcr.io/pterodactyl/yolks:java_17`
  * [`java17 - OpenJ9`](https://github.com/Clouds-Studios/Docker-Images/tree/master/java/17j9)
    * `ghcr.io/pterodactyl/yolks:java_17j9`
  * [`java18`](https://github.com/Clouds-Studios/Docker-Images/tree/master/java/18)
    * `ghcr.io/pterodactyl/yolks:java_18`
  * [`java18 - OpenJ9`](https://github.com/Clouds-Studios/Docker-Images/tree/master/java/18j9)
    * `ghcr.io/pterodactyl/yolks:java_18j9`
  * [`java19`](https://github.com/Clouds-Studios/Docker-Images/tree/master/java/19)
    * `ghcr.io/pterodactyl/yolks:java_19`
  * [`java19 - OpenJ9`](https://github.com/Clouds-Studios/Docker-Images/tree/master/java/19j9)
    * `ghcr.io/pterodactyl/yolks:java_19j9`
  * [`java21`](https://github.com/Clouds-Studios/Docker-Images/tree/master/java/21)
    * `ghcr.io/pterodactyl/yolks:java_21`
