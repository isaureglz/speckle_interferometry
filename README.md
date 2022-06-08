# speckle_interferometry

This Python script was produced in the context of the C2PU (Centre Pédagogique Planète Univers) module of the MAUCA (Master track in Astrophysics in Université Côte d'Azur). The goal was to retrieve the angular diameter of asteroid Ceres using speckle interferometry, following the technique of Antoine Labeyrie. After computing the average power spectrum of Ceres, we derived its Fourier transform: the visibility. After applying an apodization on the visibility, we can retrieve the angular frequency which is directly linked to the angular diameter.
