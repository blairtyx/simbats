basic_soruces = ['FiniteField.cpp', 'BatchDec.cpp', 'BatchEnc.cpp'];

env = Environment()
debug = ARGUMENTS.get('debug', 1)
if int(debug):
    env.Append(CCFLAGS = '-g')
else:
    env.Append(CCFLAGS = '-O3')
simbats = env.Program('simbats', ['simBats.cpp']+basic_soruces)


