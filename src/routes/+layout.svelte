<script>

    import Navbar from "./navbar.svelte";

</script>

<Navbar />

<slot />

<footer class="footer">
    <div class="container">
        <div class="columns">
            <div class="column is-three-fifths">
                <span class="copyright">
                    Azure Cost Estimator is a product of The Cloud Theory.
                </span>
            </div>
            <div class="column">
                <strong>About</strong>
                <ul>
                    <li>Company</li>
                    <li>Products</li>
                    <li>FAQ</li>
                    <li>Contact</li>
                </ul>
            </div>
            <div class="column">
                <strong>Azure Cost Estimator</strong>
                <ul>
                    <li>Use cases</li>
                    <li>Documentation</li>
                    <li>GitHub</li>
                </ul>
            </div>
            <div class="column">
                <strong>Ecosystem</strong>
                <ul>
                    <li>Azure Cost Estimator</li>
                    <li>Bicep.Docs</li>
                    <li>Workout</li>
                    <li>Spotter</li>
                </ul>
            </div>
        </div>
    </div>
</footer>