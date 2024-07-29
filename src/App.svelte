<script>
  import { Router, Route } from 'svelte-routing';
  import Home from './lib/Components/Home.svelte';
  import ProductDetails from './lib/Components/ProductDetails.svelte';
</script>

<Router>
  <Route path="/" component={Home} />
  <Route path="product/:id" component={ProductDetails} />
</Router>


