<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>DockFilterX: Ligand Filtering Criteria</title>
</head>
<body>
    <h1>DockFilterHub: Ligand and Protein Filtering Criteria</h1>
    <p><strong>DockFilterX</strong> is a Python-based filtering system for docking data, focusing on ligand diversity, protein-ligand interactions, and conformation validation. It ensures high-quality ligands by applying Tanimoto similarity filtering, energy-based screening, and molecular property validation.</p>
    <h2>Features</h2>
    <ul>
        <li>Filters ligands based on <strong>Tanimoto similarity</strong> to remove redundancies.</li>
        <li>Evaluates protein-ligand interactions using <strong>energy-based thresholds</strong>.</li>
        <li>Validates ligands for <strong>3D conformation, non-polymeric structure, supported elements, and non-racemic mixtures</strong>.</li>
    </ul> 
    <h2>Installation</h2>
    <p>Clone the repository and install dependencies:</p>
    <pre>
        git clone https://github.com/your-repo/DockFilterX.git
        cd DockFilterX
        pip install -r requirements.txt
    </pre>
    <h2>Usage</h2>
    <p>Run the ligand filtering script:</p>
    <pre>
        python filter_ligands.py --folder_path /path/to/ligand/folder --threshold 0.8
    </pre> 
    <p>Run the protein-ligand interaction filtering:</p>
    <pre>
        python filter_interactions.py --protein_folder /path/to/protein --ligand_folder /path/to/ligands --threshold -7.0
    </pre> 
    <h2>Validation Example</h2>
    <pre>
        python validate_ligand.py --sdf_file /path/to/ligand.sdf
    </pre>
    <h2>Acknowledgements</h2>
    <p><strong>Author:</strong> Gajulapalli Naga Vyshnavi</p>
    <p><strong>Contact:</strong> nvyshnavi36@gmail.com</p>
    <p>For any inquiries, feel free to reach out via the contact info above.</p>
</body>
</html>
