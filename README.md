# Public audit reports
This repository collects all our reports that have been published by our clients.

## Verifying report signatures
From a certain date the reports have a signature that can be used to verify that the pdf has not been modified when downloaded from a source other than this repository.

- Download the `public.key` file
- Import it with gpg and verify

```
gpg --import public.key
gpg --verify <report>.pdf.sig <report>.pdf
```
