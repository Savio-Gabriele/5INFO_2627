<script>
    let { 
        nome = "Mario", 
        cognome = "Rossi", 
        age = "99" 
    } = $props();
    let url = 'https://png.pngtree.com/png-vector/20220709/ourmid/pngtree-businessman-user-avatar-wearing-suit-with-red-tie-png-image_5809521.png';
</script>

<div>
    <h1>Ciao sono {nome} {cognome} ho {age} anni</h1>
    <h4>Sono studente all'istituto agnelli di torino</h4>
    <img src={url} alt="">    
</div>
