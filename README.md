# MichelleTech
`gradle build`

`gradle runClient`

I will clean up the codebase for this project *after* I learn the basics of modding.
No need to hassle shaping cookies that don't have sugar in them.

### Resources
https://docs.neoforged.net/

https://docs.neoforged.net/docs/gettingstarted/

### Other stuff
By default, the MDK is configured to use the official **mapping names** from Mojang for methods and fields 
in the Minecraft codebase. These names are covered by a specific license. All modders should be aware of this
license. For the latest license text, refer to the mapping file itself, or the reference copy here:
https://github.com/NeoForged/NeoForm/blob/main/Mojang.md

If at any point you are missing libraries in your IDE, or you've run into problems you can
run `gradle --refresh-dependencies` to refresh the local cache. `gradle clean` to reset everything 
{this does not affect your code} and then start the process again.
