# atom-gpg package

GPG Encryption for Atom. Encrypts and decrypts selected text.

## Install

### Dependencies

  - gpg

```bash
$ apm install atom-gpg
```

Or install trough Atom Packages.

## Settings

If you get error message "Failed to spawn command gpg. Make sure gpg is installed and on your PATH" then you need to go to Settings page and set `Gpg Executable` path.

## Usage

Select text and press ```ctrl-shift-e``` to encrypt or ```ctrl-shift-d``` to decrypt.

Optionally you can also use context menu with right mouse button and select either _GPG Encrypt_ or
_GPG Decrypt_. Same options can be found under menu __Packages__ -> __GPG__.

You can encrypt and decrypt multiple selections simultaniously.

### Recipients

You need to specify recipients to encryption. You can either specify them on Settings `Gpg recipients` or have `gpg.recipients` file in the same directory or in root of Git repo. User IDs in the file will be appended to recipients define in the Settings.
