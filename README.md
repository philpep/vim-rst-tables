Author: Li Chao <1983.chao@gmail.com>


This plugin is based on reStructuredText tables plugin:
http://www.vim.org/scripts/script.php?script_id=3450
Edited to improve cjk character alignment, and vim_bridge not needed.
The modification is also inspired by vimscript #4272.
The original script is vimscript #3041.


Mapping example::

    map ,,c :python ReformatTable()<CR>
    map ,,f :python ReflowTable()<CR>
