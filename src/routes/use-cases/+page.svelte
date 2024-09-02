<script lang="ts">
    import useCase1 from '$lib/assets/use-case-1.PNG';
    import useCase2 from '$lib/assets/use-case-2.PNG';
    import useCase3 from '$lib/assets/use-case-3.PNG';
    import useCase4 from '$lib/assets/use-case-4.PNG';
</script>

<svelte:head>
	<title>Azure Cost Estimator - automated cost estimations for ARM Templates, Bicep and Terraform - Use cases</title>
	<meta name="description" content="Azure Cost Estimator is a FOSS project aimed at providing cost estimations for Azure infrastructure." />
    <style>
        .hero {
            background-color: #39a1ff;
            color: white;
        }

        .hero .title, .hero .subtitle {
            color: white;
        }
    </style>
</svelte:head>

<section class="homepage hero is-medium">
    <div class="hero-body">
        <div class="container">
            <div class="columns">
                <div class="column">
                    <p class="title">Azure Cost Estimator.</p>
                    <p class="subtitle">Use cases</p>                    
                </div>
            </div>       
        </div>  
    </div>
</section>

<section class="section">
    <div class="container">
        <div class="columns is-centered">
            <div class="column has-text-centered">
                <h2 class="title">Learn how Azure Cost Estimator can help you in your daily tasks</h2>
                <h3 class="subtitle">All it takes is downloading one file and integrating it with your CICD pipelines.</h3>
            </div>
        </div>      
    </div>
</section>

<section class="section">
    <div class="container">
        <div class="columns is-centered">
            <div class="column">
                <h2 class="title">Enhancing FinOps initiatives</h2>
                <p>
                    Be proactive in your cloud spendings. With Azure Cost Estimator, you can have a clear view of your infrastructure costs before deploying it. You can also use it to generate reports and integrate them with your FinOps dashboards.
                </p>
            </div>
            <div class="column">
                <img src={useCase1} alt="Azure Cost Estimator" />
            </div>
        </div>
    </div>
</section>

<section class="section">
    <div class="container">
        <div class="columns is-centered">
            <div class="column">
                <img src={useCase2} alt="Azure Cost Estimator" />
            </div>
            <div class="column">
                <h2 class="title">Preventing unpredicted charges</h2>
                <p>
                    Azure Cost Estimator can help you to prevent unpredicted charges by providing you with a clear view of your infrastructure costs and blocking deployments that exceed your budget. Configure your thresholds and let Azure Cost Estimator do the rest.
                </p>
            </div>
        </div>
    </div>
</section>

<section class="section">
    <div class="container">
        <div class="columns is-centered">
            <div class="column">
                <h2 class="title">Focusing on development</h2>
                <p>
                    Calculating infrastructure costs can be time-consuming. With Azure Cost Estimator, you can focus on developing your applications and let Azure Cost Estimator do the rest. It will provide you with an accurate cost estimation in seconds.
                </p>
            </div>
            <div class="column">
                <img src={useCase3} alt="Azure Cost Estimator" />
            </div>
        </div>
    </div>
</section>

<section class="section">
    <div class="container">
        <div class="columns is-centered">
            <div class="column">
                <img src={useCase4} alt="Azure Cost Estimator" />
            </div>
            <div class="column">
                <h2 class="title">Controlling your budget</h2>
                <p>
                    Thanks to Azure Cost Estimator, you can have a clear view of your infrastructure costs and control your budget. You can set up thresholds and block deployments that exceed your budget. You can also use webhooks to integrate it with your existing tools and update current cloud spendings based on the provided estimations.
                </p>
            </div>
        </div>
    </div>
</section>