��� ������������� �������� ����� �������� ������ ����� � scriptpath ��� ���������� ���������� � ������������ ����� (��-���������, CDS_SITE\pcb\scripts).

set_grid.scr - ����� �����.
������ ������������� � env:
funckey CF1 'set grid_val 11; replay set_grid.scr'
funckey g 'settoggle grid_val 0.1 0.2 0.25 0.5 1; replay set_grid.scr'
alias ~G 'settoggle grid_val 0.635 1.27 2.54; replay set_grid.scr'


set_width.scr - ����� ������� �����.
������ ������������� � env:
funckey w 'settoggle line_width 0.2 0.25 0.4 0.5 1.0 2.0; replay set_width.scr'
alias ~W 'set line_width Constrain; replay set_width.scr' 