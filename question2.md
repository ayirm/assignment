**Question2**  Please assign variables to the individual components of your favorite gene! (e.g.
promoter, 5' UTR, start codon, exon1, intron, exon2, stop codon, 3' UTR). Print the entire gene 
by using the string concatenation operator, on the standard output! Note: Feel free to create a 
fictional gene sequence by randomly filling in the gene components by the characters 
corresponding to individual nucleotide bases.

## My Favorite Gene

Let's create a representation of my favorite gene by assigning variables to its individual components:

```python
# Gene components
promoter = "TATAAAG"
5_utr_prime = "ATGCTA"
start_codon = "ATG"
exon1 = "AGTCTAG"
intron = "GTACGTA"
exon2 = "CTAGCTA"
stop_codon = "TAA"
3_utr = "AATTAG"

# Concatenate gene components
favorite_gene = promoter + 5_utr_prime + start_codon + exon1 + intron + exon2 + stop_codon +3_utr

# Print the entire gene
print(favorite_gene)
