<script lang="ts">
  import Fa from 'svelte-fa'
  import { faGithub, faTwitter } from '@fortawesome/free-brands-svg-icons'
  import { faFilePdf } from '@fortawesome/free-solid-svg-icons'
</script>

<main>
	<header>
    <div>
      <h1>Interactive, Visual Uncertainty Quantification</h1>
      <h2>for Encrypted Network Traffic Situation Awareness</h2>
      <div>Harry X. Li, Allan Wollaber</div>
      <br/>
      <div style="font-size:2em">
        <a href="https://github.com/harryli0088/interactive-visual-uncertainty-quantification" target="_blank" rel="noopener noreferrer">
          <Fa class="icon-button" icon={faGithub} style="color:white;"/>
        </a>
      </div>
      <br/>
      <div><i>Presented at <a href="https://vizsec.org/vizsec2021/" target="_blank" rel="noopener noreferrer">VizSec21</a>, <a href="certificate-best-poster.pdf" target="_blank" rel="noopener noreferrer">Best Poster</a></i></div>
      
    </div>
  </header>

  <section>
    <a href="Interactive_Visual_Uncertainty_Quantification_Poster.pdf" target="_blank" rel="noopener noreferrer">
      <button style="background-color:#FF5733;outline: none;border: none;color:white">
        Full Poster <Fa icon={faFilePdf}/>
      </button>
    </a>
    &nbsp;
    <a href="Interactive_Visual_Uncertainty_Quantification_Abstract.pdf" target="_blank" rel="noopener noreferrer">
      <button style="background-color:#F39C12;outline: none;border: none;color:white">
        Full Abstract <Fa icon={faFilePdf}/>
      </button>
    </a>
    &nbsp;
    
    <button style="background-color:rgb(29, 155, 240);border-radius:50%">
      <a href="https://twitter.com/VizSec/status/1449746373927075840" target="_blank" rel="noopener noreferrer" style="color:white">
        <Fa icon={faTwitter}/>
      </a>
    </button>

    <h2>Demo Video</h2>
    <video width="100%" height="auto" controls style="background-color:gray">
      <source src="Interactive_Visual_Uncertainty_Quantification_Demo.mp4" type="video/mp4">
      Your browser does not support the video tag :( but you can view it <a href="Interactive_Visual_Uncertainty_Quantification_Demo.mp4" target="_blank" rel="noopener noreferrer">here</a>
    </video>

    <!-- <img src="Interactive_Visual_Uncertainty_Quantification_Image.png" alt="screenshot"/> -->

    <p>
      As machine learning-based applications reach the hands of operators, the models often struggle to communicate the confidence of their predictions. Operators may end up blindly trusting a model, unaware that the model is only marginally confident or has never seen the input data during training. We present a visualization dashboard for encrypted network traffic labels that combines confidence sliders and visualizations to contextualize the model’s uncertainty.
    </p>

    <!-- Bib? -->
  </section>

  <section>
    <h2>Distribution Statement</h2>

    <p>All the documents including the poster, abstract, videos, and descriptive text have this distribution statement:</p>

    <b>DISTRIBUTION STATEMENT A. Approved for public release. Distribution is unlimited.</b> This material is based upon work supported under Air Force Contract No.
FA8702-15-D-0001. Any opinions, findings, conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of
the U.S. Air Force. © 2021 Massachusetts Institute of Technology. Delivered to the U.S. Government with Unlimited Rights, as defined in DFARS Part 252.227-7013 or
7014 (Feb 2014). Notwithstanding any copyright notice, U.S. Government rights in this work are defined by DFARS 252.227-7013 or DFARS 252.227-7014 as detailed
above. Use of this work other than as specifically authorized by the U.S. Government may violate any copyrights that exist in this work.
  </section>
</main>

<style>
	header {
		display: flex;
		align-items: center;
		justify-content: center;
		overflow: hidden;
		background-color: #17202A;
		color: white;
    text-align: center;
    height: 70vh;
	}
  @media only screen and (min-width: 600px) {
		header {
			height: 50vh;
		}
	}

  /* img {
    width: 100%;
  } */
</style>