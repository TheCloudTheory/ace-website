<script lang="ts">
    import hero1 from '$lib/assets/hero-1.PNG';
    import hero2 from '$lib/assets/hero-2.PNG';
    import feat1 from '$lib/assets/feat-1.PNG';
    import feat2 from '$lib/assets/feat-2.PNG';
    import feat3 from '$lib/assets/feat-3.PNG';
    import feat4 from '$lib/assets/feat-4.PNG';
    import feat5 from '$lib/assets/feat-5.PNG';
</script>

<svelte:head>
	<title>Azure Cost Estimator - automated cost estimations for ARM Templates, Bicep and Terraform</title>
	<meta name="description" content="Azure Cost Estimator is a FOSS project aimed at providing cost estimations for Azure infrastructure." />
    <style>
        .hero img {
            box-shadow: 0px 0px 20px #9af2ff;
            position: absolute;
        }

        img.img1 {
            top: -13rem;
            left: 0;
        }

        img.img2 {
            top: -16rem;
            left: 14rem;
            width: 95%;
            z-index: 1;
        }

        .hero {
            background-color: #39a1ff;
            color: white;
        }

        .hero .title, .hero .subtitle {
            color: white;
        }
    </style>
</svelte:head>

<section class="homepage hero is-large">
    <div class="hero-body">
        <div class="container">
            <div class="columns">
                <div class="column">
                    <p class="title">Don't let your monthly bill to surprise you.</p>
                    <p class="subtitle">Estimate infrastructure cost with ease for free.</p>                    
                </div>
                <div class="column is-relative">
                    <img src={hero1} alt="Azure Cost Estimator" class="img1" />
                    <img src={hero2} alt="Azure Cost Estimator" class="img2" />
                </div>
            </div>       
        </div>  
    </div>
</section>

<section class="section">
    <div class="container">
        <div class="columns is-centered">
            <div class="column has-text-centered">
                <h2 class="title">Why Azure Cost Estimator?</h2>
                <h3 class="subtitle">Learn how Azure Cost Estimator can help you with automated estimations for Azure infrastructure.</h3>
            </div>
        </div>      
    </div>
</section>

<section class="section">
    <div class="container">
        <div class="columns is-centered">
            <div class="column">
                <h2 class="title">Native support for ARM Templates and Bicep</h2>
                <p>
                    Azure Cost Estimator fully understands the structure of both ARM Templates and Bicep files. It extracts all the necessary information to provide you with an accurate cost estimation. No additional configuration is needed - use the same concepts you are already familiar with.
                </p>
            </div>
            <div class="column">
                <img src={feat1} alt="Azure Cost Estimator" />
            </div>
        </div>
    </div>
</section>

<section class="section">
    <div class="container">
        <div class="columns is-centered">
            <div class="column">
                <img src={feat2} alt="Azure Cost Estimator" />
            </div>
            <div class="column">
                <h2 class="title">Seamless CICD integration</h2>
                <p>
                    Do you want to integrate Azure Cost Estimator into your CICD pipeline? No problem! Azure Cost Estimator works with any CICD tool making it easy to automate cost estimations for your infrastructure. You can treat it as safety net for your deployments, blocking them if the cost is too high.
                </p>
            </div>
        </div>
    </div>
</section>

<section class="section">
    <div class="container">
        <div class="columns is-centered">
            <div class="column">
                <h2 class="title">Human-friendly output options</h2>
                <p>
                    Azure Cost Estimator provides you with a human-friendly output. It shows you the cost estimation in a way that is easy to understand. You can see the cost of each resource, the total cost of the infrastructure, and the cost of the infrastructure per month. You can also decide if you want to see the cost in USD or any other currency and select formatting which suits you best.
                </p>
            </div>
            <div class="column">
                <img src={feat3} alt="Azure Cost Estimator" />
            </div>
        </div>
    </div>
</section>

<section class="section">
    <div class="container">
        <div class="columns is-centered">
            <div class="column">
                <img src={feat4} alt="Azure Cost Estimator" />
            </div>
            <div class="column">
                <h2 class="title">No external dependencies</h2>
                <p>
                    Don't worry if you are using Azure Cost Estimator in a secure environment as it doesn't require any external dependencies to work. It is a standalone application that you can run on your machine or in your environment without any additional setup. 
                </p>
            </div>
        </div>
    </div>
</section>

<section class="section">
    <div class="container">
        <div class="columns is-centered">
            <div class="column">
                <h2 class="title">No hidden cost</h2>
                <p>
                    Azure Cost Estimator is a free and open-source project. You can use it without any limitations and without any hidden costs. You can also contribute to the project and help us make it even better.
                </p>
            </div>
            <div class="column">
                <img src={feat5} alt="Azure Cost Estimator" />
            </div>
        </div>
    </div>
</section>