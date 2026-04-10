---
layout: project
title: ODP 5
description: ""
image: /assets/images/ODP5coverimage.png
technologies: [CAD, Prototyping]
permalink: /projects/odp5/
hidden_from_projects: true
---
# Save the Grapes!!


**Team:** Save the Grapes

## Design Documentation
<p style="text-align: center;">
  <img
    src="{{ "/assets/images/bom.png" | relative_url }}"
    alt="BOM"
    style="max-width: 600px; width: 80%; height: auto;"
  />
</p>

## Design Intent
<p style="text-align: center;">
  <img
    src="{{ "/assets/images/designintent_sketch.png" | relative_url }}"
    alt="Design Intent Sketch"
    style="max-width: 600px; width: 80%; height: auto;"
  />
</p>

## CAD Assembly

<div style="max-width: 1100px; margin: 2rem auto; text-align: center;">

  <figure style="margin: 0 0 2rem 0;">
    <img
      src="{{ "/assets/images/assemblymain.png" | relative_url }}"
      alt="Main CAD assembly view"
      style="width: 100%; max-width: 950px; height: auto; display: block; margin: 0 auto;"
    />
  </figure>

  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 2rem; justify-items: center; align-items: start;">
    <figure style="margin: 0; width: 100%; max-width: 420px;">
      <div style="height: 370px; display: flex; align-items: center; justify-content: center;">
        <img
          src="{{ "/assets/images/assemblyunder.png" | relative_url }}"
          alt="CAD assembly underside view"
          style="max-width: 100%; max-height: 100%; width: auto; height: auto; display: block; margin: 0 auto;"
        />
      </div>
    </figure>

    <figure style="margin: 0; width: 100%; max-width: 420px;">
      <div style="height: 370px; display: flex; align-items: center; justify-content: center;">
        <img
          src="{{ "/assets/images/assemblywide.png" | relative_url }}"
          alt="CAD assembly wide view"
          style="max-width: 100%; max-height: 100%; width: auto; height: auto; display: block; margin: 0 auto;"
        />
      </div>
    </figure>
  </div>

</div>

## Assembly Process

### Box Base
<ol>
  <li>Cut four balsa planks to 10 in using a hand saw.</li>
  <li>Cut one plank to 8 in using a hand saw.</li>
  <li>Attach two 10 in pieces parallel using 4 screws and the two 3D-printed top attachments to create the top.</li>
  <li>
    Connect a top plank to a side plank perpendicularly with the corner attachment.
    <ol type="a">
      <li>Insert screw with a washer on each side and secure with a nut.</li>
      <li>Use two of these corner attachments per side.</li>
      <li>Corner attachments should always be connected to a top piece.</li>
    </ol>
  </li>
  <li>
    Repeat this step until it is a box without a front or a bottom.
    <ol type="a">
      <li>All pieces should be connected to the top.</li>
    </ol>
  </li>
  <li>Take the 3D-printed frame and attach it in the same way using corner attachments.</li>
  <li>
    Use hinges to attach the 3D-printed door to the frame.
    <ol type="a">
      <li>Attach with screws, washers, and nuts.</li>
    </ol>
  </li>
  <li>Cut a hole through the middle using a hole saw.</li>
</ol>

### PVC Pipe &amp; Tubing
<ol>
  <li>Dremel a hole in the PVC pipe 4.5 in up from the bottom for wrapped tubing to exit out of.</li>
  <li>Dremel a hole in the PVC pipe 1.5 in from the top for wrapped piping to go back inside.</li>
  <li>Dremel a hole 2 in from the bottom of the PVC pipe.</li>
  <li>Cut the 25 ft plastic 5 mm tubing into one 43 in piece (inner) and one 96 in piece (wrapped).</li>
  <li>
    Run inner tubing through the middle of the PVC pipe and connect to the smallest hole in the center of the shower head.
    <ol type="a">
      <li>Secure with tape.</li>
    </ol>
  </li>
  <li>Exit it on the bottom through the hole 2 in from the bottom.</li>
  <li>Run wrapped tubing through the bottom of the PVC pipe and out the first hole (4.5 in from bottom).</li>
  <li>
    Wrap the tubing around the PVC pipe until the hole at the top.
    <ol type="a">
      <li>Secure with tape.</li>
    </ol>
  </li>
  <li>Push tubing through the hole at the top and back down the pipe, but through the center now, and exit it at the hole 2 in from the bottom.</li>
  <li>Place the PVC pipe with wrapped tubing through the hole in the box.</li>
  <li>Go through and, every 1/16 in, make a very small slash in the wrapped tubing outside using the X-Acto knife.</li>
</ol>

## Design Test
Our testing process verified two different aspects of our prototype, both of which involved the pumping of water from the base to the top of the product. Water was used as the test fluid due to its accessibility and similar qualities to our final fluid we will use. Our first test examined fluid flow from the pump out of the tubing that wrapped around the PVC pipe. We used an Xacto knife to make small incisions in the tubing to enable water to flow out of it. These incisions will closely, if not exactly, reflect how we will create holes in our final product. We measured incision flow in time intervals of 2.5 mins due to our assumption that the flow rate would be very small, which would make it difficult to measure the flow rate on a seconds based time interval. Also, we chose minutes as our time scale because we intend to have the fluid in the final product last several days before being refilled. We were unable to measure on a time scale of hours because our lab time did not allow for it. We used a measuring device graduated in 10 mL increments when measuring flow rates.

<div style="max-width: 1000px; margin: 2rem auto 1rem auto; display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 2.5rem; align-items: start;">
  <figure style="margin: 0; text-align: center;">
    <div style="height: 400px; display: flex; align-items: center; justify-content: center;">
      <img
        src="{{ "/assets/images/datatable1.png" | relative_url }}"
        style="max-width: 100%; max-height: 100%; width: auto; height: auto;"
      />
    </div>
    <figcaption style="font-weight: 700; font-size: 2rem; margin-top: 0.75rem;">
      Data Table 1
    </figcaption>
  </figure>

  <figure style="margin: 0; text-align: center;">
    <div style="height: 400px; display: flex; align-items: center; justify-content: center;">
      <img
        src="{{ "/assets/images/image1.png" | relative_url }}"
        style="max-width: 100%; max-height: 100%; width: auto; height: auto;"
      />
    </div>
    <figcaption style="font-weight: 700; font-size: 2rem; margin-top: 0.75rem;">
      Image 1
    </figcaption>
  </figure>
</div>

<p style="max-width: 1000px; margin: 1rem auto 3rem auto; line-height: 1.7;">
  <strong>Data Table 1</strong> shows our results from the incision flow. Based on
  <strong>Data Table 1</strong>, our average flow rate was 3 mL/min, confirming our
  assumption that incision flow would be very small. <strong>Image 1</strong> shows
  the water that was used in the tube and coming out of the tube, which confirmed a
  part of our success criteria.
</p>

<div style="max-width: 1000px; margin: 2rem auto 1rem auto; display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 2.5rem; align-items: start;">
  <figure style="margin: 0; text-align: center;">
    <div style="height: 400px; display: flex; align-items: center; justify-content: center;">
      <img
        src="{{ "/assets/images/datatable2.png" | relative_url }}"
        style="max-width: 100%; max-height: 100%; width: auto; height: auto;"
      />
    </div>
    <figcaption style="font-weight: 700; font-size: 2rem; margin-top: 0.75rem;">
      Data Table 2
    </figcaption>
  </figure>

  <figure style="margin: 0; text-align: center;">
    <div style="height: 400px; display: flex; align-items: center; justify-content: center;">
      <img
        src="{{ "/assets/images/image2.png" | relative_url }}"
        style="max-width: 100%; max-height: 100%; width: auto; height: auto;"
      />
    </div>
    <figcaption style="font-weight: 700; font-size: 2rem; margin-top: 0.75rem;">
      Image 2
    </figcaption>
  </figure>
</div>

<p style="max-width: 1000px; margin: 1rem auto 0 auto; line-height: 1.7;">
  <strong>Data Table 2</strong> shows the results from the flow rate from the shower
  head design experiment. The flow rate for the shower head design was noticeably
  higher than the incision design (factor of 30x). This matched our expectations
  because we had a much larger cross-sectional area in the shower head for the water
  to flow when compared with the incision design. <strong>Image 2</strong> shows the
  shower head design experiment. We propped the shower head at a height similar to
  where it would stand on the final product in order to gauge flow rate at a non-zero
  height above the pump. This is important because the higher the water has to be
  pumped, the slower the flow rate will be.
</p>

## Success Criteria

<p>
  Context: We are looking to create a fake grape vine to attract lantern flies away
  from vineyards so they don’t destroy real grape vines. Once we have attracted the
  lantern flies away from the real grape vines, we are then able to ethically dispose
  of them.
</p>

<p>
  Looking at the next step in our timeline, which is refining some of our tests and
  design from this prototype, we noticed a couple of issues in our current tests that
  could be refined.
</p>

<h2 style="margin-top: 2rem;">Project Success Criteria</h2>

<div style="margin-left: 2.25rem; margin-top: 2rem;">
  <p style="font-size: 1.6rem; font-weight: 700; margin-bottom: 0.75rem;">
    (1) Sap Fluid Drainage at a rate &lt; 20 mL/hr
  </p>
  <p style="margin-left: 3.25rem; max-width: 900px; line-height: 1.6;">
    Since our sap slowly leaks out of the holes along the wrapped tubing, we want to
    make sure that it does not drain out too quickly in order to save maintenance
    time spent refilling. Looking at our data right now, we have a drainage rate of
    around 180 mL/hr for the sap, so we definitely want to cut that down in the
    future. To do this, we could slow the drive voltage from the power source or try
    a clamp on one of the ends to limit the flow. If we have the flow at 20 mL an
    hour, the sap would need to be replaced around once a day considering a 500 mL
    reservoir at the bottom. This could easily be tested again using our pump and
    tracking volume. Since this is a representation of our smaller scaled model, it
    would probably be around once a week for the larger “real world” model when
    scaled up.
  </p>
</div>

<div style="margin-left: 2.25rem; margin-top: 3rem;">
  <p style="font-size: 1.6rem; font-weight: 700; margin-bottom: 0.75rem;">
    (2) Vinegar Sprayer Spraying Radius of &gt; 0.25 m
  </p>
  <p style="margin-left: 3.25rem; max-width: 900px; line-height: 1.6;">
    When thinking about our concept, we wanted to make sure that our vinegar does
    not really spray anything but the distraction so that it would not affect the
    grapes. With that, we want to make sure that our radius is limited to 0.25 m.
    We did not measure radius this time, so it will be interesting to see what our
    next set of tests shows. The radius could be measured by placing a paper
    underneath our contraption and running the shower system for around 30 seconds
    to see where the farthest droplet lands on the paper underneath. In terms of
    design criteria to maximize this, we could redesign our shower head to cave
    inward like an umbrella so the spray faces the PVC pipe.
  </p>
</div>

<div style="margin-left: 2.25rem; margin-top: 3rem;">
  <p style="font-size: 1.6rem; font-weight: 700; margin-bottom: 0.75rem;">
    (3) Electronics and Fluid Storage Contained within a 320 cubic inch Volume
  </p>
  <p style="margin-left: 3.25rem; max-width: 900px; line-height: 1.6;">
    We have limited space for the reservoirs in the boxes underneath, so both the
    vinegar and sap reservoirs, along with the electronics, have to fit. For this,
    we would have to maximize the fluid storages while still prioritizing the safety
    of the electronics.
  </p>
</div>

<h2 style="margin-top: 3rem; margin-bottom: 2rem;">Demonstration Day Criteria</h2>

<p style="max-width: 1000px; line-height: 1.6; font-size: 1.05rem; margin: 0 0 2rem 0;">
  When it comes to demonstration day criteria, one of the most relevant is the
  success of the vinegar sprayer spraying radius being greater than 0.25 m. This is
  because it is a clear visual for those in the audience that we were able to get a
  key mechanical system working, but also that we would be able to kill lantern
  flies in a wide area that are on our system.
</p>
