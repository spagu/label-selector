# label-selector
Adds a label to the PR if any not added. Check across whole organization and label same branches. Update a status page.

```yaml
labels-selector:
    avalible-labels: ['label1', 'label2', 'label3']
    documentation: 
        format: md
        link: 'link to the wiki page'
    action: if-avalible|nothing|delete
    organization: none|name
    data_storage: global.DEPLOYMENTS_MATRIX
```
