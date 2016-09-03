# Images CSV File Format

## Columns

* **FriendlyName** - Used as the file name for the image.
* **SKU** - The name of index number of the edition to use from the ISO/WIM file.  eg. "Professional" or "ServerDataCenter"
* **Arch** - x64 or x86. Used to set Is32Bit parameter. Needed to create the unattend file correctly.
* **Generation** - Create a generation 1 or 2 virtual machine.
* **Desktop** - Set to TRUE for desktop windows versions. Creates a regular user account, which is required by the desktop unattended installation.
* **ProductKey** - The product key to use for the unattended installation.
* **Image** - The ISO or WIM file to use as the base of the windows image.
* **SHA1** - The SHA1 hash of Image. Not used by Image Factory.
* **Version** - [Version of Windows](https://en.wikipedia.org/wiki/Windows_NT). Used to sort file. Not used by Image Factory.
* **Notes** - User notes. Not used by Image Factory.
