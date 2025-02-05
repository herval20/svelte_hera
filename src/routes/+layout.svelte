<script>

    //Import of the app.css used for the whole project
	import '../app.css';
	
    
    // Props mean the properties 
    //@Render is one comand always used in layout.svelte
    let { children } = $props();
</script>



{@render children()}
