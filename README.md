# Octo-Say 🐙💬
**Octo-Say** is a simple GitHub Action created to help developers learn automation in a fun way. It works like a "Hello World" but with a creative touch.

## What does it do?

The action connects to the official GitHub API to get an ASCII art of the **Octocat**. Then, it combines the Octocat image with a custom message that you choose and displays it directly in your GitHub Actions console.

## Key Features

- **Easy to use:** Perfect for testing your first workflow.
- **API Integration:** It shows how a GitHub Action can talk to an external API.
- **Visual Feedback:** Instead of just text, you get a cool visual response in your logs.

## How to use it

To use this action in your project, add these lines to your `.github/workflows/main.yml` file:

```yaml
- name: Run Octo-Say
	uses: odonML/octo-say@v2
	with:
		message: "hello, world"
```
Note: This action only supports plain text and spaces. Special characters are not allowed

## Output action in console:

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

## Input for octo-say:
Note: This action only supports plain text and spaces. Special characters are not allowed

| Input | Description | Required | Default |
| --- | --- | --- | --- |
| `message` | The text you want the Octocat to say. | Yes | "Hello World" |
