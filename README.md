# Jquery

## What does it do?

The module uncludes jQuery into Magento from 1.5.x to 1.7.x via Layout Updates.


## How to use?

Just import and enjoy.


## Dependencies

None.


## FAQ

### What if it doesn't work?

Well, this could happen if your Magento version ist lower or higher than the above mentioned ones. If your version is higher, just leave an issue, so we can fix it. Another possible reason could be that you've implemented your own theme. The Layout Update may not be executed - in this case, just copy the corresponding Layout file into your theme:

app/design/frontend/base/default/layout/sota/jquery.xml


### I would like to update the libs by myself - how do I?

* Drop the scripts into js/sota/jquery.
* Update script call within app/design/frontend/[package]/[theme]/layout/sota/jquery.xml (by default line 24+)