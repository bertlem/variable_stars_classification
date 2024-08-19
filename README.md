# Variable stars classification

## 1 - Lomb-Scargle periodogram

The Lomb-Scargle periodogram is a commonly used statistical tool designed to detect periodic signals in unevenly spaced observations, that are typical in astrophysics.

Indeed, celestial objects are not always observable (for most spectral windows, only during the night!), their observability depends in addition on the period of the year (only a few regions can be observed all year long, and a close-by full Moon is a problem when observing faint objects). The weather conditions can also hamper astronomical observations: the presence of clouds is an obvious case, but even moderate winds may also prevent from opening the domes, for instance. Finally, observations can only occur when observing time is granted (after a stark competition) to a given team.

The first notebook in this project illustrates Lomb-Scargle periodograms obtained for a few selected periodic variable stars observed in the I band by the OGLE team. We experiment with two flavours of the Lomb-Scargle periodogram, one provided by astropy and the other provided by scipy.

For the (randomly selected) examples, we note that both algorithms provide very similar results for two of the selected varable stars. For the third star, the scipy algorithm ends up with a wrong relative intensity for the peaks, and in turn with a wrong period as the method implies that the fundamental period of the variable star corresponds to the most prominent peak.
