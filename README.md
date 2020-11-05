To reproduce run `yarn reproduce` on top level

## Problem

Cannot require `pnpapi` from script located outside the yarn workspace

This is a big problem when you want to test a dev tool that uses `pnpapi` (in my case i am trying to use my local version of [vite](https://github.com/vitejs/vite) in a yarn pnp repo)
