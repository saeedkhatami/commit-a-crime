[![Auto commit](https://github.com/saeedkhatami/commit-a-crime/actions/workflows/autocommit.yml/badge.svg)](https://github.com/saeedkhatami/commit-a-crime/actions/workflows/autocommit.yml)

# "Commit" a crime

Making green your Github contributions via [Github Actions](https://github.com/features/actions)

## Make it your own


- Create your own repo with click "**Use this template**" button (forked repo will not work)

Or just do in the manual way:

- Create your own repo
- Copy file `.github/workflows/autocommit.yml` and `LAST_UPDATED` to your repo
- Change the `email` and `name` information on file [autocommit.yml, line 29 and 30](https://github.com/saeedkhatami/Commit-a-crime/blob/master/.github/workflows/autocommit.yml#L29)
- Change the scheduling time on file [autocommit.yml, line 10](https://github.com/saeedkhatami/Commit-a-crime/blob/master/.github/workflows/autocommit.yml#L10). You can use [crontab.guru](https://crontab.guru/) if you are not familiar with the cron schedule string. For first time, you can try to run it in every hour with string `1 * * * *` .
- Consider to support me, at least click the 🌟 button




## Credits

- [Github Actions](https://github.com/features/actions)
- [ad-m/github-push-action](https://github.com/ad-m/github-push-action)
