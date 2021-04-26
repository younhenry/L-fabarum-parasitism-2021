This subfolder contains the raw data in a single txt file

The file has the following columns:

- `Replicate`:  
- `Aphid_line`: unique ID for the host × *Hamiltonella* line that is tested here
- `Parasitoid_line`: unique ID for the parasitoid line that is tested here	 
- `Block`:  
- `Latitude`, `Longitude`: coordinates of the collection site for the `Parasitoid_line`
- `Wasp_host_species`: the original **aphid** species from which the *parasitoid* wasp line was collected 
- `Hamiltonella_host_species`: the original **aphid** species from which the *Hamiltonella* line was collected 
- `Nymphs_corrected`: number of aphid nymphs that were counted  
- `Dead_wasp`:  
- `Mummies_amount`: number of aphid nymphs that were mummified (contained successfully developing wasps) (≤ `Nymphs_corrected`)
- `Hatching_wasps`: number of emerging adult wasps **that were detected** (finding adult wasps is not trivial) (≤ `Hatching_wasps`) 
- `Field_hamiltonella_presence`:  