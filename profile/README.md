![logo](./img/logo-name.png)

</br></br>

## Overmind: Terraform Impact Analysis

Overmind gives you confidence to move faster with Terraform no matter how large, complex, old, manually created, inconsistent or otherwsie scary your environment is!

## Blast Radius

Use our [GitHub action](https://github.com/overmindtech/actions) to go from **Terraform Plan --> Blast Radius**. The blast radius is based on your live AWS/Kubernetes state, not Terraform, which lets you see what might break:

* Includes **resources not managed by Terraform**
* Discovers dependencies **even if they were created manually**
* Shows *live data*, not out-of-date CMDB data

![blast radius](./img/blast_radius.png)

## Impact Analysis (diff)

Once you've decided to apply your changes, track them with Overmind. SInce we've already worked out all the dependencies, we can tell you if you changes has broken something downstream, even if you didn't know it existed.

![blast radius diff](./img/blast_radius_diff.png)
