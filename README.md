# Detypify Data

## Data Format

The design goal of the format is to be human-readable and easy-to-diff.

- Each symbol has a text file named `<symbol-name>.txt`.
- In the file, each line contains one sample.
- Samples are JSONs with the type of `Strokes` shown below:
  ```python
  type Point = tuple[int, int]
  type Stroke = list[Point]
  type Strokes = list[Strokes]
  ```

## License

MIT
