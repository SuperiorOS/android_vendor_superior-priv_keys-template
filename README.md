
A cool template to sign SuperiorOS builds with `dev-keys`.

## Usage

1. Clone the repository 

```
croot && git clone https://github.com/SuperiorOS/android_vendor_superior-priv_keys-template.git vendor/superior-priv/keys 
```

2. Go to the key directory 

```
cd vendor/superior-priv/keys
```

3. Run the script

```
./keys.sh
```

It will generate the certificates in vendor/superior-priv/keys.

Backup AT ALL COSTS your vendor/superior-priv/keys folders AND NEVER LEAK THOSE. Losing these keys could prevent you from updating your SuperiorOS builds with the same keys, so formatting data would be required. Leakage of these keys can compromise the security and authenticity of your builds, requiring a new pair of keys to be generated.