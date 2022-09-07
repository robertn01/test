# Covid-19 Genomics UK Consortium

Spike protein structures showing locations of amino acid residues that are mutated in each variant of concern (VOC). The spike protein protrudes from the surface of the SARS-CoV-2 virus, is responsible for initating binding to and entry into host cells, and is also the primary target for antibodies that recognise the virus.

Consult our own Metadata Catalogue for the
* [[COG UK metadata|COGUK_metadata]] metadata (e.g. `cog_metadata.csv`)
* [[COG UK naive variants|COGUK_naive_variants]] naive variants (e.g. `naive_variants.csv`)
* Consensus sequence (e.g. `cog_all.fasta`) in FASTA format
* Full alignment (e.g. `cog_alignment.fasta`) in FASTA format
* Unmasked alignment (e.g. `cog_unmasked_alignment.fasta`) in FASTA format

A note about identifiers:
* the main component of the patient identifier is the ISARIC id (in the form `ABCD-0123`)
* the ISARIC id will be given a numerical suffix (`.1`, `.2`, `.3` etc) because there may be multiple samples per patient
* the FASTA identifier has that ISARIC id surrounded by /England/ and /year/ (e.g. `/England/ABCD-0123.1/2020`)
* some patients have multiple ISARIC ids

A note about multiple samples per patient: each physical sample should be assigned exactly one COG ID and any re-sequencing of the same sample should be submitted under the same COG ID. In practise, this is not enforced (and hard to do so anyway) and submitting organisations (including PHE/UKHSA) have often issued new COG IDs for the same sample, resulting in multiple COG IDs actually referring to the same swab. Trying to de-duplicate on sample date is not entirely reliable (frequently off by a day or two in different reports) and it would also be perfectly legitimate to have more than one actually distinct samples (like a throat and a nose swab) on the same day from the same patient.

Data dictionary:

*  Data dictionary for CSV and FASTA files [COG-UK-TRE_data_dictionary_v1_020721.pdf](datadict/COG-UK-TRE_data_dictionary_v1_020721.pdf) [PDF]

*  Metadata CSV schema [cog_uk_metadata_spec_20210415.pdf](datadict/cog_uk_metadata_spec_20210415.pdf) [PDF]

Web references:

*  [FASTA format](https://en.wikipedia.org/wiki/FASTA_format)

*  [A UK-wide collaborative network for SARS-CoV-2 genomics, research and training](https://www.cogconsortium.uk/)

*  [COG UK VOC Dashboard](https://sars2.cvr.gla.ac.uk/cog-uk/)
