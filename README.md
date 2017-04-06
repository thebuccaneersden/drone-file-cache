# drone-persistent-file-storage
This Drone.ci plugin is used for persisting files across multiple builds. One such example is the local caches for Composer, NPM and Yarn - which speeds up build times, as each of these dependency managers will not have to re-download all packages on every build.
