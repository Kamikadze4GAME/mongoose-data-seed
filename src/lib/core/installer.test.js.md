# Snapshot report for `src/lib/core/installer.test.js`

The actual snapshot is saved in `installer.test.js.snap`.

Generated by [AVA](https://ava.li).

## Should _initConfig

> Snapshot 1

    {
      config: {
        configTemplatePath: '/template/folder/config-template.js',
        customSeederTemplateFilename: 'some-template.js',
        customSeederTemplatePath: '/project/root/some-template.js',
        userConfigExists: true,
        userConfigFilename: 'config-filename.js',
        userConfigFilepath: '/project/root/config-filename.js',
        userPackageJsonPath: '/project/root/package.json',
        userSeedersFolderName: 'seeders-folder',
        userSeedersFolderPath: '/project/root/seeders-folder',
      },
    }

## Should _initConfig without customSeederTemplate

> Snapshot 1

    {
      config: {
        configTemplatePath: '/template/folder/config-template.js',
        customSeederTemplateFilename: undefined,
        customSeederTemplatePath: undefined,
        userConfigExists: true,
        userConfigFilename: 'config-filename.js',
        userConfigFilepath: '/project/root/config-filename.js',
        userPackageJsonPath: '/project/root/package.json',
        userSeedersFolderName: 'seeders-folder',
        userSeedersFolderPath: '/project/root/seeders-folder',
      },
    }
