# Emerald
Emerald, a backronym for "Explore Material Entry Relationships for Analysis and
Lucid Design", aims to be a suite of tools for materials scientists to visualize,
analyze, manipulate, and track calculations for sets of materials.

## Project goals
* Seamless integration with
  the [Materials Project (MP)](https://materialsproject.org/) Python
  ([pymatgen](http://pymatgen.org/)) and public web interfaces.
* Manage and share material filters (dynamic) and lists (static).
* Manage and share visualizations/analyses based on projections
  (properties/descriptors) of material filters/lists.
* Manage "phantom" materials and descriptors that track completion of
  corresponding workflows.

## Project status
Emerald is unstable and under active development. Once the project is stable,
this repository will be transferred to
the [materialsproject](https://github.com/materialsproject/) GitHub
organization.

## Package structure
Emerald is being developed as a Python package containing one or
more [Django](https://www.djangoproject.com/) apps pluggable
with [webtzite](https://github.com/materialsproject/webtzite), which is a Django
app for mocking MP's core web interface.
