Для использования скриптов можно добавить данную папку в scriptpath или перекинуть содержимое в используемую папку (по-умолчанию, CDS_SITE\pcb\scripts).

set_grid.scr - смена сетки.
Пример использования в env:
funckey CF1 'set grid_val 11; replay set_grid.scr'
funckey g 'settoggle grid_val 0.1 0.2 0.25 0.5 1; replay set_grid.scr'
alias ~G 'settoggle grid_val 0.635 1.27 2.54; replay set_grid.scr'


set_width.scr - смена толщины линии.
Пример использования в env:
funckey w 'settoggle line_width 0.2 0.25 0.4 0.5 1.0 2.0; replay set_width.scr'
alias ~W 'set line_width Constrain; replay set_width.scr' 