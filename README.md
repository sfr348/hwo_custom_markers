# hwo_custom_markers
Custom matplotlib markers for different telescope aperture concepts for searching for exo-Earths.

python setup.py sdist bdist_wheel
twine upload dist/* --verbose

import hwo_custom_markers
markers = hwo_custom_markers.generate_custom_markers.get_custom_markers()
