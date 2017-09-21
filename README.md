# Custom Search Mode

This package contains a sample of creating a Custom Search Mode to be used in addition to the default Simple, Advanced, and AML search modes.

## History

This project and the following release notes have been migrated from the old Aras Projects page. 

Release | Notes
--------|--------
[v1](https://github.com/ArasLabs/custom-search-mode/releases/tag/v1) | Initial Release

#### Supported Aras Versions

Project | Aras
--------|------
[v1](https://github.com/ArasLabs/custom-search-mode/releases/tag/v1) | 9.3

## Installation

#### Important!
**Always back up your code tree and database before applying an import package or code tree patch!**

### Pre-requisites

1. Aras Innovator installed
2. Aras Package Import tool
3. **custom-search-mode** import packages

### Install Steps

#### Code Tree Installation

1. Backup your code tree and store the archive in a safe place.
2. Navigate to your local `..\custom-serach-mode\` folder
3. Copy the `\Innovator\` folder
4. Paste this at the root of your install directory
+ By default this is `C:\Program Files\Aras\Innovator\`

#### Database Installation

1. Backup your database and store the BAK file in a safe place.
2. Open up the Aras Package Import tool.
3. Enter your login credentials and click **Login**
  * _Note: You must login as root for the package import to succeed!_
4. Enter the package name in the TargetRelease field.
  * Optional: Enter a description in the Description field.
5. Enter the path to your local `..\custom-search-mode\Import\imports.mf` file in the Manifest File field.
6. Select all packages in the Available for Import field.
7. Select Type = **Merge** and Mode = **Thorough Mode**.
8. Click **Import** in the top left corner.
9. Close the Aras Package Import tool.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

For more information on contributing to this project, another Aras Labs project, or any Aras Community project, shoot us an email at araslabs@aras.com.

## Credits

Created by Aras Corporation Support.

## License

Aras Labs projects are published to Github under the MIT license. See the [LICENSE file](./LICENSE) for license rights and limitations.
