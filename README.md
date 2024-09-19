# Setup Yarn Action

Reduce boilerplate when installing setting up Node.js and installing Yarn dependencies.

## Usage

```yml
- uses: mskelton/setup-yarn@v3
```

## Checkout a specific Git ref

```yml
- uses: mskelton/setup-yarn@v3
  with:
   ref: ${{ github.head_ref }}
```

## Specify Node version

```yml
- uses: mskelton/setup-yarn@v3
  with:
   node-version: '16.x'
```

## Pass additional flags to the install command

```yml
- uses: mskelton/setup-yarn@v3
  with:
   flags: --immutable-cache
```
