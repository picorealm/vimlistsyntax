# vimlistsyntax

Script to list all available syntax hightlight styles for Vim.

- use Vim's :redir to output 'echo &rtp' to text file
- search Vim runtimepath (rtp) for .vim syntax definition files
- use Python os.scandir() for fast searches of directories


