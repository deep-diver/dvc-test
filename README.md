# dvc-test

## requirements
- need to decrypt `.dvc/config.gpg` and `.dvc/tmp/gdrive-user-credentials.json.gpg` using the following command
```shell
gpg --quiet --batch --yes --decrypt --passphrase="YOUR_PASSWORD" --output=.dvc/config .dvc/config.gpg
gpg --quiet --batch --yes --decrypt --passphrase="YOUR_PASSWORD" --output=.dvc/tmp/gdrive-user-credentials.json .dvc/tmp/gdrive-user-credentials.json.gpg
```
