# Repository structure

## Contents

As seen with the directories listed below

* [Worlds](worlds/index.html)
* [World Object glTFs](worldobjects/index.html)
* [World Object kits](kits/index.html)
* [Avatars](avatars/index.html)

## Entry structure

* Entry names are structured with "\<nnnn\> \<desc\>"
  * nnnn is the ordering number
  * desc depends on the entry type:
    * plain file (without extension): CID of worlds or kits
    * plain file (.glb): world object glTF or avatar glTF
    * directory
      * `contents.tar` or `contents.zip` or `contents.glb`
      * `description.json` with
        * author
        * description
      * actual name will be desc itself
      * modification will be derived from the contents file date
