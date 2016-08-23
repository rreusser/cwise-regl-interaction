# cwise-regl-interaction

(extra note: this has nothing to do with regl. it's the `requiring` of json that seems to trigger it. `regl` is merely a module that definitely triggers it.)

See: 

- [scijs/cwise#12](https://github.com/scijs/cwise/issues/12)
- [ternjs/acorn#415](https://github.com/ternjs/acorn/issues/415)

To reproduce:

```bash
git clone https://github.com/rreusser/cwise-regl-interaction.git
cd cwise-regl-interaction
npm install
npm run bundle
```
