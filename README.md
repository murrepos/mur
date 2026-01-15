# Mining under Radar: Evaluating the Detectability of Pool-Based Cryptocurrency Mining 
Artifact Instructions

This repository contains the research artifact associated with the paper under review.
Due to file size constraints, the artifact is provided as an **encrypted file split into multiple parts**.

The steps below describe how to reconstruct and decrypt the artifact.

## Artifact Access and Setup

1. Download **all parts** of the encrypted artifact:

```
mur_repo.tar.gz.gpg.part_aa
mur_repo.tar.gz.gpg.part_ab
mur_repo.tar.gz.gpg.part_ac
```


2. Reconstruct the encrypted artifact by concatenating all parts:
```bash
cat mur_repo.tar.gz.gpg.part_* > mur_repo.tar.gz.gpg
```
3. Decrypt the reconstructed file. The passphrase for decryption is provided under the Open Science Policy section in the appendix of the submission.
```bash
gpg -d mur_repo.tar.gz.gpg > mur_repo.tar.gz
```
4. Uncompress the decrypted archive:
```bash
tar -xzf mur_repo.tar.gz
```


