# Customization

The user interface can be customized through attributes, and will be inherited from a users' groups.

## Enabling/disabling features

The following features can be enabled/disabled. By default, all of them are enabled:

- `settings.enabledFeatures.apiDrawer`

    API Request drawer in navbar
- `settings.enabledFeatures.notificationDrawer`

    Notification drawer in navbar
- `settings.enabledFeatures.settings`

    Settings link in navbar
- `settings.enabledFeatures.applicationEdit`

    Application edit in library (only shown when user is superuser)
- `settings.enabledFeatures.search`

    Search bar

## Other configuration

### `settings.navbar.userDisplay`

Configure what is shown in the top right corner. Defaults to `username`. Choices: `username`, `name`, `email`

### `settings.theme.background`

Optional CSS which is applied in the background of the background of the user interface; for example

```yaml
settings:
  theme:
    background: >
      background: url('https://picsum.photos/1920/1080');
      filter: blur(8px);
      background-position: center;
      background-repeat: no-repeat;
      background-size: cover;
```

### `settings.layout.type`

Which layout to use for the Library view. Defaults to `row`. Choices: `row`, `2-column`, `3-column`

### `settings.locale`

The locale which can be configured in the user settings by default. This can be used to preset locales for groups of users, but still let them choose their own preferred locale
