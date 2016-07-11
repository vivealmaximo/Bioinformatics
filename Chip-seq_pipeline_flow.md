<h1 align="center">
Chip-seq pipe flow from raw fastq to motif-analysis and annotation 
</h1>

<p>
General outline
</p>

<ol>
  <li>
  Determination of of adequate sequence depth based on size of genome, size of binding site, frequency of binding site.
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
        Create coverage to find optimal multi-mapping or alignment programs.
        </li>
    </ul>
  </li>
  <li>
  Quality metrics of read counts
    <ul>
      <li>
      Normalized Strand cross correlation
      </li>
      <li>
      Relative Strand cross correlation
      </li>
      <li>
      PCR bottle neck coefficent 
      </li>
    </ul>
  </li>

</ol>
