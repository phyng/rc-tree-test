
# rc-tree-test

```
npm install
npm start
```

error:

```
➜  rc-tree-test git:(master) ✗ npm start

> rc-tree-test@1.0.0 start /Users/phyng/dev/packages/rc-tree-test
> tsc --version && tsc

Version 4.8.2
node_modules/rc-tree/lib/NodeList.d.ts:15:23 - error TS2344: Type 'TreeDataType' does not satisfy the constraint 'BasicDataNode'.

15     data: FlattenNode<TreeDataType>[];
                         ~~~~~~~~~~~~

  node_modules/rc-tree/lib/NodeList.d.ts:12:25
    12 interface NodeListProps<TreeDataType> {
                               ~~~~~~~~~~~~
    This type parameter might need an `extends BasicDataNode` constraint.

node_modules/rc-tree/lib/NodeList.d.ts:18:29 - error TS2344: Type 'TreeDataType' does not satisfy the constraint 'BasicDataNode'.

18     activeItem: FlattenNode<TreeDataType>;
                               ~~~~~~~~~~~~

  node_modules/rc-tree/lib/NodeList.d.ts:12:25
    12 interface NodeListProps<TreeDataType> {
                               ~~~~~~~~~~~~
    This type parameter might need an `extends BasicDataNode` constraint.


Found 2 errors in the same file, starting at: node_modules/rc-tree/lib/NodeList.d.ts:15

npm ERR! code ELIFECYCLE
npm ERR! errno 2
npm ERR! rc-tree-test@1.0.0 start: `tsc --version && tsc`
npm ERR! Exit status 2
npm ERR!
npm ERR! Failed at the rc-tree-test@1.0.0 start script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.
```
