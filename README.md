# Aplia Form token (fork of eZ Form token)

## What is Aplia Form token?

Aplia Form token is a fork of eZ Form token extension which is bundled inside the eZ Publish legacy repository.

#### How to merge with eZ Form token

1. Checkout `ezpublish-legacy`

   `git clone https://github.com/ezsystems/ezpublish-legacy`

2. Checkout Aplia Form token

   `git clone git@github.com:Aplia/ezformtoken.git aplia-ezformtoken`

3. Enter Aplia Form token

   `cd aplia-ezformtoken`

4. Remove everything except `.git`, `README.md` and `composer.json`

   `ls | grep -v '.git' | grep -v 'README.md' | grep -v 'composer.json' | xargs rm -R`

5. Copy updated code from `ezpublish-legacy`

   `cp -R ../ezpublish-legacy/extension/ezformtoken/ .`

6. Review and add changes

   `git add .`

7. Push code and add new release
