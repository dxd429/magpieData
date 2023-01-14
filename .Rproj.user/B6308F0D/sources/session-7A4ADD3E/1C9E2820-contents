#' Get the system path to the folder containing .BAM files and corresponding annotation file.
#'
#' This function is designed to accompany the package 'magpie' for use in vignette and examples.
#' These .BAM files only contain chromosome 15 data from the dataset (GEO accession: GSE46705)
#' from a study investigating METTL3-METTL14 complexmediates mammalian nuclear RNA N6-adenosine methylation. In this dataset, there are two sample types
#' from human HeLa cell line: one wild type (WT) sample and one treated sample. The treatment
#' corresponds to the knockdown (KD) of complex METTL3. Each sample contains two replicates.
#'
#' @return A system file path to the folder containing .BAM files and corresponding annotation file (hg18).
#' @export
#'
#' @examples
#' #### Get the file path
#' BAMFolder <- getBAMpath()
getBAMpath <- function() {
    dir(system.file(package = "magpieData"), "extdata", full.names = TRUE)
}
