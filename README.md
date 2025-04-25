# DATA555 Final Project - Interactive QQ plot and Manhattan plot using cell-type-specific TWAS-results

This project uses the Transcriptome-Wide Association Study results from single-nuclear RNA-sequencing data, which were derived from the Religious Orders Study (ROS) and Memory and Aging Project (MAP) cohorts1, representing a total of n = 436 participants (older persons) analyzed for six cell types (Astrocytes, Excitatory Neurons, Inhibitory Neurons, Microglia, Oligodendrocytes and Oligodendrocyte Precursor Cells). The data was collected by yearly blood draws from participants across the United States which result in the storage of serum, plasma and cells since 1994 (for ROS) and 1997 (for MAP). This dataset represents transcriptome associations between genes and Alzheimer’s Disease across all six cell types.

### Dashboard aims or research questions investigated (Relevant HTML widget(s) and tools): 
-	How do different imputation models compare in identifying statistically significant genes across six cell types? (Plotly Manhattan Plot)
-	Are there cell type specific genomic regions on chromosome that showing a higher density of significant genes? (Plotly Manhattan Plot)
-	Are the observed distributions of p-values deviating from the null expectation, suggesting real signals in each panel? (Plotly Quantile-Quantile Plot)
-	Filterable Search tool: Users can find information (Cell type, Models) for individual panel to see cell-type-specific genetic associations. (Crosstalk library)

### Real-world impact and importance of dashboard
The project helps us identify cell type specific significant risk genes associated with Alzheimer’s Disease using different statistical models. The findings could be used for future biomedical research to uncover new treatment gene target of Alzheimer’s Disease.