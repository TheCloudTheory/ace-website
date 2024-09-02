<svelte:head>
    <style>
        a.footer-link {
            color: #404654;
            display: block;
            position: relative;
        }

        a.footer-link:hover {
            text-decoration: underline;
        }
    </style>
</svelte:head>

<footer class="footer">
    <div class="container">
        <div class="columns">
            <div class="column is-three-fifths">
                <span class="copyright">
                    Azure Cost Estimator is a product of The Cloud Theory.
                </span>
            </div>
            <div class="column">
                <strong>Azure Cost Estimator</strong>
                <ul>
                    <li>
                        <a href="use-cases" class="footer-link">Use cases</a>
                    </li>
                    <li>
                        <a href="use-cases" class="footer-link">Documentation</a>
                    </li>
                    <li>
                        <a href="use-cases" class="footer-link">GitHub</a>
                    </li>
                </ul>
            </div>
            <div class="column">
                <strong>Ecosystem</strong>
                <ul>
                    <li>
                        <a href="https://github.com/TheCloudTheory/arm-estimator" class="footer-link" target="_blank">Azure Cost Estimator</a>
                    </li>
                    <li>
                        <a href="https://github.com/TheCloudTheory/bicep-docs" class="footer-link" target="_blank">Bicep.Docs</a>
                    </li>
                </ul>
            </div>
            <div class="column">
                <strong>Coming soon</strong>
                <ul>
                    <li>
                        <a href="https://github.com/TheCloudTheory/Workout" class="footer-link" target="_blank">Workout</a>
                    </li>
                    <li>
                        <a href="#" class="footer-link">INFRAck</a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</footer>