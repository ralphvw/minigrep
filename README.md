# Minigrep

Minigrep is a simple Rust command-line application for searching a specified word in a file.

## Usage

```bash
# Search for a word in a file
minigrep <word> <file_name>

# Case-insensitive search (optional)
CASE_INSENSITIVE=1 minigrep <word> <file_name>
```

## Environment Variable

- `CASE_INSENSITIVE`: Set this environment variable to make the search case-insensitive.

## Example

Search for the word "example" in a file named "sample.txt":

```bash
minigrep example sample.txt
```

Search for the word "hello" case-insensitively in the same file:

```bash
CASE_INSENSITIVE=1 minigrep hello sample.txt
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
