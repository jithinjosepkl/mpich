## Deploy MPICH to Azure Cloud

Deploy MPICH to Azure Cloud using the following "Deploy to Azure" button. It will create a head node and a set of compute nodes.
Select the HPC image to get a pre-built HPC image for the compute nodes. 
Load mpich environment module using:

```
module load mpi/mpich-3.3
```

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fjithinjosepkl%2Fazhpc%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png" />
</a>