<template>
	<div>
		<app-header/>

    <div class="hero is-link">
      <div class="container is-max-widescreen gap-on-mobile">
        <div class="columns is-desktop pt-6 pb-6">
          <div class="column is-three-fifths">
            <h1 class="title is-2 is-spaced">How does your Azure Kubernetes Architecture Design measure up?</h1>
            <p class="subtitle">
              There is no single perfect cluster design or configuration. Instead ask yourself - how well does my cluster design meet my business requirements?
            </p>
            <p>
              <a class="button is-medium is-primary" href="/review">Review your Architecture Design &rarr;</a>
            </p>
          </div>
        </div>
      </div>
    </div><!--/.hero-->

    <div class="container is-max-widescreen">
      <section class="section">
        <div class="columns is-desktop">
          <div class="column">
            <h3 class="title is-5">Reference Architectures are misleading</h3>
            <p>The official Microsoft reference architectures e.g. Contoso do not reflect the diversity of scenarios and requirements. This limits the <em>individual impact</em> of the decisions we make. We can do better.</p>
          </div>
          <div class="column">
            <h3 class="title is-5">"It depends" equals Real-Life Engineering</h3>
            <p>Cloud adoption is a <em>journey</em>. So often our decisions will be different based on previous experience, even if we have similar requirements.</p>
          </div>
          <div class="column">
            <h3 class="title is-5">No free fish, teaching you to fish</h3>
            <p>This means the app refrains from prescriptive recommendations. Instead the focus is to help you <em>make a decision</em> and understand the <em>consequences</em> of that decision across multiple dimensions.</p>
          </div>
        </div>
      </section>

      <section class="section">
        <Nuxt/>
      </section>
    </div>


		<app-footer/>
	</div>
</template>