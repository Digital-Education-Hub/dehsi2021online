+++
title = "Command line"
+++

Your pattern documentation may need to include commands for installing packages or using <abbr title="command line interface">CLI</abbr>s. **Cupper** offers the `cmd` shortcode for making code blocks look like terminal commands.

Here's how you write it:

And here's how it looks:

{{<cmd>}}
npm run start
{{</cmd>}}

{{% warning %}}
The `cmd` shortcode currently only supports single commands. If you want to show multiple, successive commands use separate `cmd` blocks.
{{% /warning %}}
