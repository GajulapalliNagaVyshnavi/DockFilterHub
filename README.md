<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
</head>
<body>
    <h1>DockFilterHub: Ligand and Protein Filtering Criteria</h1>
    <p><strong>DockFilterHub</strong> is a Python-based filtering system for docking data, focusing on ligand diversity, protein-ligand interactions, and conformation validation. It ensures high-quality ligands by applying Tanimoto similarity filtering, energy-based screening, and molecular property validation.</p>
    <h2>Features</h2>
    <ul>
        <li>Filters ligands based on <strong>Tanimoto similarity</strong> to remove redundancies.</li>
        <li>Evaluates protein-ligand interactions using <strong>energy-based thresholds</strong>.</li>
        <li>Validates ligands for <strong>3D conformation, non-polymeric structure, supported elements, and non-racemic mixtures</strong>.</li>
    </ul> 
    <h2>Installation</h2>
    <p>Clone the repository and install dependencies:</p>
    <pre><code>
        git clone https://github.com/your-repo/DockFilterX.git
        cd DockFilterHub
        pip install required installations
    </code></pre>
        <h2>Usage</h2>
    <p>DockFilterhub is implemented as a Jupyter Notebook. To run it:</p>
    <ol>
        <li>Open the Jupyter Notebook:
            <pre><code>jupyter notebook</code></pre>
        </li>
        <li>Navigate to <code>Docking_filtering_criteria_1.ipynb</code> and execute the cells step by step or use those functions in your code accordingly </li>
        <li>Provide your <strong>ligand and protein file paths</strong> in the notebook.</li>
        <li>The system will return whether the given data meets the filtering criteria (<code>True</code> or <code>False</code>).</li>
    </ol>
    <h2>Acknowledgements</h2>
    <p>Author: Gajulapalli Naga Vyshnavi<br>
    Contact: <a href="mailto:nvyshnavi36@gmail.com">nvyshnavi36@gmail.com </a><br>
    For any inquiries, feel free to reach out via the contact information provided.</p>
</body>
</html>
