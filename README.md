<h1> This pipeline is to generate the joint angles and their corresponding deviations </h1>
<ol>Order of running the files:
<li>angles_combined.ipynb
    <ul>
      <li>This generates the joint angles.</li>
    </ul>
    </li>
<li>deviations.ipynb
<ul>
  <li>This generates the deviations and plots them against time. 
      <ul>
          <li>
              Deviations are calculated by taking the absolute differences of the joint angles and dividing them by the true (MoCap) value.
              The output of angles_combined.ipynb is the input to this file.
          </li>
      </ul>
      </li>
</ul>
</li>  
</ol>

<p>Sample outputs of differences.csv and the deviation PDF are attached.</p>
