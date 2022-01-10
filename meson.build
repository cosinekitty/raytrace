project('raytrace', 'cpp', default_options: ['optimization=3'])

raytrace = executable('raytrace', sources: [
    'lodepng/lodepng.cpp',
    'raytrace/algebra.cpp',
    'raytrace/binary.cpp',
    'raytrace/chessboard.cpp',
    'raytrace/cuboid.cpp',
    'raytrace/cylinder.cpp',
    'raytrace/debug.cpp',
    'raytrace/dodecahedron.cpp',
    'raytrace/icosahedron.cpp',
    'raytrace/main.cpp',
    'raytrace/optics.cpp',
    'raytrace/planet.cpp',
    'raytrace/reorient.cpp',
    'raytrace/scene.cpp',
    'raytrace/setcompl.cpp',
    'raytrace/setisect.cpp',
    'raytrace/setunion.cpp',
    'raytrace/solid.cpp',
    'raytrace/sphere.cpp',
    'raytrace/spheroid.cpp',
    'raytrace/thinring.cpp',
    'raytrace/torus.cpp',
    'raytrace/triangle.cpp',
])

test('tests', raytrace, args: ['test'])
