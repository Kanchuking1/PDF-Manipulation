# PDF-Manipulation

Currently this repository only has support for pdf appending

```

pip install
python .\pdf_append.py <path-to-files-in-order> ...

```

## Example:
The following code would generate a results.pdf with contents of bunny-dancing.pdf followed by contents of transcript.pdf 
```

python .\pdf_append.py bunny-dancing.pdf transcript.pdf

```
Similarly more than two pdfs can be appended
```

python .\pdf_append.py bunny-dancing.pdf transcript.pdf comments.pdf

```
