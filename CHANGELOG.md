# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [v0.0.1] - 2024-10-09
### Added
- Add `save_iters` and `output_path`to `mixedstate_ptychography.py` and `mixedstate_multislice_ptychography.py` to save results at certain iterations. The object, probe, and position_px are all saved.
- Add `iter_times` using cuda.Event for timing. The `iter_times` are printed at each iteration and saved with the model output
- Add print to `__init__.py` to specify it's loaded from a local editable repo