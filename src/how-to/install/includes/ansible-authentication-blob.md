::: note
::: title
Note
:::

If you use ssh *keys*, and the user you login with is either
[root]{.title-ref} or can elevate to [root]{.title-ref} without a
password, you don\'t need to do anything further to use ansible. If,
however, you use password authentication for ssh access, and/or your
login user needs a password to become root, see
`ansible-authentication`{.interpreted-text role="ref"}.
:::
