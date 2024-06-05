# hwo_custom_markers
Custom matplotlib markers for different telescope aperture concepts for searching for exo-Earths.

import hwo_custom_markers
import matplotlib.pyplot as plt
markers = hwo_custom_markers.generate_custom_markers.get_custom_markers()

plt.figure()
plt.plot(1,1,ls='', marker=custom_markers[aperture_name],  markerfacecolor='k', markeredgecolor='k', markersize=30)

Note if you want the mirror faces to be different colours, plot a square behind it:
plt.figure()
plt.plot(1, 1, ls='', marker='s',  markerfacecolor='m', markeredgecolor='m', markersize=30)
plt.plot(1, 1, ls='', marker=custom_markers[aperture_name], markerfacecolor='k', markeredgecolor='k', markersize=30)
