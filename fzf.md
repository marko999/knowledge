# copy files from-to using fzf, prompts target file and target directory on systemcp 
`$(find . -type f | fzf --prompt="Select file to copy: ") $(find . -type d | fzf --prompt="Select destination directory: ")`
