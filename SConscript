from building import *

# get current directory
cwd     = GetCurrentDir()
# The set of source files associated with this SConscript file.
src     = Glob('*.c')

path    = [cwd]

CPPDEFINES = ['MG_LOCALS']

group = DefineGroup('Mongoose', src, depend = [''], CPPPATH = path, CPPDEFINES = CPPDEFINES)

Return('group')
