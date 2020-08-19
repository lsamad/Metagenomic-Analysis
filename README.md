# Metagenomic-Analysis
$fasterq-dump SRR1016450.1
./fastq-dump -Z SRR1016451 > kebrit_16s.fastq
conda create --name ngs
source activate ngs
conda install -c bioconda fastqc
conda install -c bioconda trimmomatic
conda install -c bioconda/label/cf201901 bioconvert
conda config --add channels r
 conda config --add channels defaults
  conda config --add channels conda-forge
  conda config --add channels bioconda
conda install bioconvert
get "ftp://ftp-trace.ncbi.nlm.nih.gov/sra/sdk/current/sratoolkit
module load sratoolkit
