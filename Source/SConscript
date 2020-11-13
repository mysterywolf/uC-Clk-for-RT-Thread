Import('rtconfig')
from building import *

cwd = GetCurrentDir()
src	= Glob('*.c')

CPPPATH = [cwd]

group = DefineGroup('uC-Clk', src, depend = ['PKG_USING_UC_CLK'], CPPPATH = CPPPATH)

Return('group')
