# Create an Entity Package

{% hint style="warning" %}
Entity packages are only required at the beginning of a network. If the network is already running then this will no longer be used.
{% endhint %}

In order to join at the beginning of the Amber Network, or at the beginning of any network \(including Oasis Mainnet\), we require that you send an Entity Package so that we can create the genesis document for a either network.

## Details

To create an Entity Package you must create a tarball \(`.tar.gz`\) that contains the following files:

* `entity/entity_genesis.json` - This is the `entity_genesis.json` from the entity you initialized.
* `entity/entity.json` - This is the `entity.json` file from the entity you initialized.
* `node/node_genesis.json` - This is the `node_genesis.json` from the node you initialized.

{% hint style="success" %}
During genesis creation we will only accept a single node.
{% endhint %}

The following commands should be executed on your local system, where you [initialized your Entity and Node](running-a-node.md#initializing-an-entity):

```text
mkdir -p package/entity package/node
cp /localhostdir/entity/*.json package/entity
cp /localhostdir/node/node_genesis.json package/node
cd package && tar -zcvf ../<YOUR-GITHUB-USERNAME>-entity.tar.gz entity node
```

## Submitting Your Entity Package \(For the Amber Network\)

{% hint style="warning" %}
The deadline for Amber Network Entity Packages is 2020-06-15T23:59:00 UTC.
{% endhint %}

To submit your Entity Package, we've created a repository that will consume and validate the Entity packages.

1. Fork the [oasisprotocol/amber-network-entities](https://github.com/oasisprotocol/amber-network-entities) repository.
2. Add your Entity Package to the `entities/` directory of the repository.
3. Create a pull request against the `master` branch of the [oasisprotocol/amber-network-entities](https://github.com/oasisprotocol/amber-network-entities) repository.  


   Once your Entity Package passes all validation checks we will handle the merging of your pull request.

You can see an example of a submission in [this PR](https://github.com/oasisprotocol/amber-network-entities/pull/1).

{% hint style="info" %}
If there are any issues, you can always resubmit your entity package.
{% endhint %}
