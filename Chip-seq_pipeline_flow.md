<h1 align="center">
Chip-seq pipe flow from raw fastq to motif-analysis and annotation 
</h1>

<p>
General outline
</p>

<ol>
  <li>
  Determination of adequate sequence depth based on size of genome, size of binding site, frequency of binding site.
  </li>
  
  <li>
  Quatily metrics of sequenced reads.
    <ul>
        <li>
        Total number of sequences.
        </li>
        <li>
        Per base sequence quality.
        </li>
        <li>
        GC-content.
        </li>
        <li>
        Over-represented sequences.
        </li>
        <li>
        K-mer content.
        </li>
    </ul>
  </li>
  
  <li>
  Alignment to reference genome
    <ul>
        <li>
        Create coverage to find optimal multi-mapping, duplication levels, or alignment programs.
        </li>
        <li>
        Assess coverage of input libraries.
        </li>
    </ul>
  </li>
  
  <li>
  Quality metrics of alignments
    <ul>
      <li>
      Normalized Strand Cross Correlation (NSC)
      </li>
      <li>
      Relative Strand Cross Correlation (RSC)
      </li>
      <li>
      PCR Bottle neck Coefficent (PBC) 
      </li>
      <li>
      Nonredundant Fraction (NRF) 
      </li>
      <li>
      Pearson/Spearman correlation between aligned samples. 
      </li>
      <li>
      Assess Chip samples signal strength.
      </li>
    </ul>
  </li>
  
  <li>
  Peak-Finding
    <ul>
        <li>
        Peak Finding using False Discovery Rate (FDR), p-values, q-values.
        </li>
        <li>
        Irreproducuble Discovery Rate
        </li>
    </ul>
  </li>
  
  <li>
  Differential binding analysis
    <ul>
      <li>
      Hypothesis Testing on multiple overlapping sets of peaks.
      </li>
      <li>
      Total count or read density of peak regions.
      </li>
    </ul>
  </li>
</ol>

<h1 align="center">
Determination of adequate sequence depth based on size of genome, size of binding site, frequency of binding site. 
</h1>
