# Octo-say :copilot: :cat:
It's just an action that aims to be a "hello world", with octocat greeting the user.

example use action octo-say:
```yaml
name: Octo-Say Demo
on:
  push:
    branches: [main]

jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - name: OctoSay
        uses: odonML/octo-say@v1
        with:
            user-name: "odonml"
```

and result in console:
```
               MMM.           .MMM
               MMMMMMMMMMMMMMMMMMM
               MMMMMMMMMMMMMMMMMMM      _______________
              MMMMMMMMMMMMMMMMMMMMM    |               |
             MMMMMMMMMMMMMMMMMMMMMMM   | Hello, odonml |
            MMMMMMMMMMMMMMMMMMMMMMMM   |_   ___________|
            MMMM::- -:::::::- -::MMMM    |/
             MM~:~ 00~:::::~ 00~:~MM
        .. MMMMM::.00:::+:::.00::MMMMM ..
              .MM::::: ._. :::::MM.
                 MMMM;:::::;MMMM
          -MM        MMMMMMM
          ^  M+     MMMMMMMMM
              MMMMMMM MM MM MM
                   MM MM MM MM
                   MM MM MM MM
                .~~MM~MM~MM~MM~~.
             ~~~~MM:~MM~~~MM~:MM~~~~
            ~~~~~~==~==~~~==~==~~~~~~
             ~~~~~~==~==~==~==~~~~~~
                 :~==~==~==~==~~
```
