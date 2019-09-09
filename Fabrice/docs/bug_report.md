# How Do I Submit A (Good) Bug Report?

Bugs are tracked as GitHub issues. After you've determined which repository your bug is related to, create an issue on that repository and provide the following information by filling in the template.

## Explain the problem and include additional details to help maintainers reproduce the problem:

Use a clear and descriptive title for the issue to identify the problem.
    Describe the exact steps which reproduce the problem in as many details as possible. For example, start by explaining how you started VS Code, e.g. which command exactly you used in the terminal, or how you started VS Code otherwise. When listing steps, don't just say what you did, but explain how you did it. For example, if you moved the cursor to the end of a line, explain if you used the mouse, or a keyboard shortcut or a VS Code command, and if so which one?
    Provide specific examples to demonstrate the steps. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use Markdown code blocks.
    Describe the behavior you observed after following the steps and point out what exactly is the problem with that behavior.
    Explain which behavior you expected to see instead and why.
    Include screenshots and animated GIFs which show you following the described steps and clearly demonstrate the problem. If you use the keyboard while following the steps, record the GIF with the Keybinding Resolver shown. You can use this tool to record GIFs on macOS and Windows, and this tool or this tool on Linux.
    If you're reporting that VS Code crashed, include a crash report with a stack trace from the operating system. On macOS, the crash report will be available in Console.app under "Diagnostic and usage information" > "User diagnostic reports". Include the crash report in the issue in a code block, a file attachment, or put it in a gist and provide link to that gist.
    If the problem is related to performance or memory, include a CPU profile capture with your report.
    If Chrome's developer tools pane is shown without you triggering it, that normally means that you have a syntax error in one of your themes or in your styles.less. Try running in Safe Mode and using a different theme or comment out the contents of your styles.less to see if that fixes the problem.
    If the problem wasn't triggered by a specific action, describe what you were doing before the problem happened and share more information using the guidelines below.

## Provide more context by answering these questions:

Can you reproduce the problem in safe mode?
    Did the problem start happening recently (e.g. after updating to a new version of VS Code) or was this always a problem?
    If the problem started happening recently, can you reproduce the problem in an older version of VS Code? What's the most recent version in which the problem doesn't happen? You can download older versions of VS Code from the releases page.
    Can you reliably reproduce the issue? If not, provide details about how often the problem happens and under which conditions it normally happens.
    If the problem is related to working with files (e.g. opening and editing files), does the problem happen for all files and projects or only some? Does the problem happen only when working with local or remote files (e.g. on network drives), with files of a specific type (e.g. only JavaScript or Python files), with large files or files with very long lines, or with files in a specific encoding? Is there anything else special about the files you are using?

## Include details about your configuration and environment:

Which version of VS Code are you using? You can get the exact version by running VS Code -v in your terminal, or by starting VS Code and running the Application: About command from the Command Palette.
    What's the name and version of the OS you're using?
    Are you running VS Code in a virtual machine? If so, which VM software are you using and which operating systems and versions are used for the host and the guest?
    Which packages do you have installed?
    Are you using local configuration files to customize VS Code? If so, provide the contents of those files, preferably in a code block or with a link to a gist.
    Are you using VS Code with multiple monitors? If so, can you reproduce the problem when you use a single monitor?
    Which keyboard layout are you using? Are you using a US layout or some other layout?
