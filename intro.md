<!-- TOP -->
<div class="top">
  <img class="scenario-academy-logo" src="https://datastax-academy.github.io/katapod-shared-assets/images/ds-academy-2023.svg" />
  <div class="scenario-title-section">
    <span class="scenario-title">Read Repair</span>
    <span class="scenario-subtitle">ℹ️ For technical support, please contact us via <a href="mailto:academy@datastax.com">email</a>.</span>
  </div>
</div>

<!-- CONTENT -->
<main>
  <br/>
  <div class="container px-4 py-2">
    <div class="row g-4 py-2 row-cols-1 row-cols-lg-1">
      <div class="feature col div-choice">
        <div class="scenario-description">DS201 Exercise 14: Read Repair</div>
          <ul>
            <li><span class="scenario-description-attribute">Difficulty</span>: Beginner</li>
            <li><span class="scenario-description-attribute">Time</span>: 10 minutes</li>
          </ul>
          <div class="scenario-objectives">In this hands-on lab, you will:</div>
            <ul>
              <li><span class="scenario-objective">Simulate an inconsistent replica node by deleting its data files</span></li>
              <li><span class="scenario-objective">Force a read repair by requesting query results from all replica nodes</span></li>
            </ul>
            <p>
              Consistency is the tricky challenge for distributed systems. As distributed systems trade-off consistency for performance, some of the nodes in a cluster may become inconsistent. When Cassandra notices these inconsistencies, it takes steps to resolve them. This resolution is the role of read repair.
            </p>
          </div>  
          <a href='command:katapod.loadPage?[{"step":"step1"}]' class="btn btn-primary btn-cassandra">
            Start the lab
          </a>
         </div>
      </div>
    </div>
  </div>
</main>