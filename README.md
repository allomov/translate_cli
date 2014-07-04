Translate_cli
=============

This tool helps when doing translations for the cloudfoundry cli.

It basically brings all the translations into one big file so that you only need to edit one file instead of many.

## Usage

Reading all translations and generation the big file:

```bash
  $ ./translate_cli es r
  $ all_es generated with translations for es
```

You can modify this new file and do some translations:

```
  $ vim all_es
```

Now its time to write those translations in the cli:

```
  $ ./translate_cli es w
  $ 1 translations were applied in /home/ubuntu/gosource/src/github.com/cloudfoundry/cli/cf/i18n/resources/es/cf/command_runner/es_ES.all.json
  $ 2 translations were applied in /home/ubuntu/gosource/src/github.com/cloudfoundry/cli/cf/i18n/resources/es/cf/terminal/es_ES.all.json
```

