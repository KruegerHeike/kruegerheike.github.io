---
title: "Talks"
layout: gridlay
sitemap: false
permalink: /talks/
---

## Talks

<div class="section-card"> <h3>Locations</h3> <p>Selected locations of invited talks and conference presentations. Click on a marker to view the event, date, and location.</p>

<div id="talk-map" style="height: 520px; width: 100%; border-radius: 12px; margin-top: 1rem;"></div> </div>

<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css">

<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>

<script> document.addEventListener("DOMContentLoaded", function () { var map = L.map("talk-map"); L.tileLayer("https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png", { maxZoom: 18, attribution: "&copy; OpenStreetMap contributors" }).addTo(map); var talks = [ { title: "Künstliche Intelligenz in der Forschung: Erfahrungen aus den Sozialwissenschaften und Perspektiven für die Versorgungsforschung", event: "Bonner Netzwerk für Versorgungsforschung", date: "5 May 2026", location: "Bonn, Germany", lat: 50.7374, lng: 7.0982 }, { title: "Potential of Social Network Analysis for Sociological Research", event: "PGR Session, Department of Sociology, Durham University", date: "13 November 2025", location: "Durham, United Kingdom", lat: 54.7753, lng: -1.5849 }, { title: "From stress to support: How mental health, mood, and biosignals shape social interaction networks over time", event: "Department of Sociology, Durham University", date: "13 November 2025", location: "Durham, United Kingdom", lat: 54.7753, lng: -1.5849 }, { title: "Adolescent Mental Health and Perceptual Accuracy in Social Support and Friendship Networks", event: "Research Seminar, Professur für Psychotherapie und Interventionspsychologie", date: "12 May 2025", location: "Würzburg, Germany", lat: 49.7913, lng: 9.9534 }, { title: "Who talks about whom? Mental Distress, Selection, and Exposure in Adolescent Gossip Networks", event: "8th European Conference on Social Networks 2026", date: "13 August 2026", location: "Linköping, Sweden", lat: 58.4108, lng: 15.6214 }, { title: "From stress to support: How mood and biosignals shape social interaction networks over time", event: "Society for Ambulatory Assessment (SAA) 2026 Conference", date: "4 August 2026", location: "Vienna, Austria", lat: 48.2082, lng: 16.3738 }, { title: "From Mood and Stress to Support: Modeling How Affective States and Wearable Biosignals Shape Social Interaction Events", event: "7th Mobile Apps and Sensors in Surveys (MASS) Workshop", date: "4 June 2026", location: "Barcelona, Spain", lat: 41.3851, lng: 2.1734 }, { title: "PeerSmart Network Study – Soziale Interaktionsnetzwerke und Biosignale im studentischen Alltag", event: "10th Congress of the German Society for Network Research", date: "9 October 2025", location: "Bayreuth, Germany", lat: 49.9456, lng: 11.5713 }, { title: "Discrepancies in the perception of social support relationships and mental health", event: "European Consortium for Sociological Research 2025 Annual Conference", date: "3 September 2025", location: "Cologne, Germany", lat: 50.9375, lng: 6.9603 }, { title: "From stress to support: How mood and biosignals shape social interaction networks over time", event: "Sunbelt Conference", date: "29 June 2025", location: "Paris, France", lat: 48.8566, lng: 2.3522 }, { title: "Inkonsistente Wahrnehmungen sozialer Beziehungen in gleich- und gegengeschlechtlichen Dyaden", event: "Spring Conference of the DGS Section Sociological Network Research", date: "13 March 2025", location: "Cologne, Germany", lat: 50.9375, lng: 6.9603 }, { title: "Peer-Smart Network Study – A Pilot Study Integrating Smartphone-Based Experience Sampling, Social Network Analysis and Wearable Sensor Data", event: "User-centered Longitudinal Collection of Digital Behavioral and Survey Data", date: "25 November 2024", location: "Mannheim, Germany", lat: 49.4875, lng: 8.4660 }, { title: "Inkonsistente Wahrnehmungen sozialer Unterstützungsbeziehungen in gleich- und gegengeschlechtlichen Dyaden", event: "9th Congress of the German Society for Network Research", date: "28 October 2024", location: "Darmstadt, Germany", lat: 49.8728, lng: 8.6512 }, { title: "Harmony on the Plate: Peer Networks and the Evolution of Adolescent Vegetarian Practices", event: "Sunbelt Conference", date: "29 June 2024", location: "Edinburgh, United Kingdom", lat: 55.9533, lng: -3.1883 }, { title: "The SOCIALBOND Project – Perspectives of a Student Survey for Health Research", event: "8th Congress of the German Society for Network Research", date: "26 October 2023", location: "Heidelberg, Germany", lat: 49.3988, lng: 8.6724 }, { title: "Dual perspectives in social support relationships", event: "7th European Conference on Social Networks (EUSN 2023)", date: "6 September 2023", location: "Ljubljana, Slovenia", lat: 46.0569, lng: 14.5058 }, { title: "Dual perspectives in social support relationships", event: "Spring Conference of the DGS Section Sociological Network Research", date: "15 March 2023", location: "Braunschweig, Germany", lat: 52.2689, lng: 10.5268 }, { title: "Mode of Contact with Friends and Mood Changes in German Adolescents during the COVID-19 Pandemic – An Ecological Momentary Assessment Study", event: "European Sociological Association (ESA) RN21 Midterm Conference 2022", date: "6 October 2022", location: "Salamanca, Spain", lat: 40.9701, lng: -5.6635 }, { title: "Everyday discrimination, social support, and mood changes in young immigrants in Germany", event: "European Association of Social Psychology (EASP) Meeting: The Role of Emotions in Interethnic Relations", date: "8 September 2022", location: "Utrecht, Netherlands", lat: 52.0907, lng: 5.1214 }, { title: "The conditional effects of stress on cognitive enhancement", event: "The Ethical, Legal, and Social Aspects of Cognitive Enhancement Strategies", date: "24 August 2021", location: "Cologne, Germany", lat: 50.9375, lng: 6.9603 }, { title: "Co-Development of Social Isolation, Loneliness and Mental Health in Adolescence", event: "Spring Conference of the DGS Section Sociological Network Research", date: "18 March 2021", location: "Wuppertal, Germany", lat: 51.2562, lng: 7.1508 }, { title: "Social Isolation, Perceived Loneliness and Mental Health in Adolescence", event: "Sunbelt Virtual Conference", date: "13 July 2020", location: "Paris, France", lat: 48.8566, lng: 2.3522 }, {
title: "From stress to support: How mental health, mood, and biosignals shape social interaction networks over time",
event: "Social Network Analysis in Scotland (SNAS) Seminar Series",
date: "10 March 2026",
location: "Edinburgh, Scotland (digital talk)",
lat: 55.9533,
lng: -3.1883
}, { title: "Peer Support Networks and Personality Trait Development in Adolescence. A Social Network Analysis of Reciprocal Causation using RSiena", event: "How Networks Matter. Theoretical, Methodological and Empirical Advances on Network Mechanisms and Effects", date: "6 February 2020", location: "Bremen, Germany", lat: 53.0793, lng: 8.8017 } ]; var markers = L.featureGroup();

talks.forEach(function (talk) {
var marker = L.marker([talk.lat, talk.lng])
.bindPopup(
"<strong>" + talk.location + "</strong><br>" +
"<em>" + talk.title + "</em><br>" +
talk.event + "<br>" +
talk.date
);

markers.addLayer(marker);
});

markers.addTo(map);

map.fitBounds(markers.getBounds(), {
padding: [40, 40]
}); </script>

<div class="section-card">
  <h3>Invited Talks</h3>

  <ul>
    <li><strong>Krüger, 5 May 2026.</strong> <em>Künstliche Intelligenz in der Forschung: Erfahrungen aus den Sozialwissenschaften und Perspektiven für die Versorgungsforschung.</em> Bonner Netzwerk für Versorgungsforschung.Dortmund. </li> 
    <li><strong>Krüger, 10 March 2026.</strong> <em>From stress to support: How mental health, mood, and biosignals shape social interaction networks over time.</em> Social Network Analysis in Scotland (SNAS) Seminar Series, Edinburgh, Scotland (digital talk).</li> 
    <li><strong>Krüger, 13 November 2025.</strong> <em>Potential of Social Network Analysis for Sociological Research.</em> PGR Session, Department of Sociology, Durham University.</li> 
    <li><strong>Krüger, 13 November 2025.</strong> <em>From stress to support: How mental health, mood, and biosignals shape social interaction networks over time.</em> Department of Sociology, Durham University.</li> 
    <li><strong>Krüger, 12 May 2025.</strong> <em>Adolescent Mental Health and Perceptual Accuracy in Social Support and Friendship Networks.</em> Research Seminar, Professur für Psychotherapie und Interventionspsychologie, University of Würzburg.</li>
  </ul>
</div>

<div class="section-card">
  <h3>Conference Presentations</h3>

  <ul>
    <li><strong>Krüger, 13 August 2026.</strong> <em>Who talks about whom? Mental Distress, Selection, and Exposure in Adolescent Gossip Networks.</em> 8th European Conference on Social Networks 2026, Linköping University.</li>
    <li><strong>Krüger, 4 August 2026.</strong> <em>From stress to support: How mood and biosignals shape social interaction networks over time.</em> Society for Ambulatory Assessment (SAA) 2026 Conference, University of Vienna.</li>
    <li><strong>Krüger, 4 June 2026.</strong> <em>From Mood and Stress to Support: Modeling How Affective States and Wearable Biosignals Shape Social Interaction Events.</em> 7th Mobile Apps and Sensors in Surveys (MASS) Workshop, Pompeu Fabra University.</li> 
    <li><strong>Krüger, 9 October 2025.</strong> <em>PeerSmart Network Study – Soziale Interaktionsnetzwerke und Biosignale im studentischen Alltag.</em> 10th Congress of the German Society for Network Research, University of Bayreuth.</li> 
    <li><strong>Krüger, 3 September 2025.</strong> <em>Discrepancies in the perception of social support relationships and mental health.</em> European Consortium for Sociological Research 2025 Annual Conference, University of Cologne.</li> 
    <li><strong>Krüger, 29 June 2025.</strong> <em>From stress to support: How mood and biosignals shape social interaction networks over time.</em> Sunbelt Conference, Paris.</li> 
    <li><strong>Krüger, Grund, and Roth, 13 March 2025.</strong> <em>Inkonsistente Wahrnehmungen sozialer Beziehungen in gleich- und gegengeschlechtlichen Dyaden.</em> Spring Conference of the DGS Section Sociological Network Research, Technische Hochschule Köln.
    </li> <li><strong>Krüger, 25 November 2024.</strong> <em>Peer-Smart Network Study – A Pilot Study Integrating Smartphone-Based Experience Sampling, Social Network Analysis and Wearable Sensor Data.</em> User-centered Longitudinal Collection of Digital Behavioral and Survey Data, GESIS Mannheim.</li> 
    <li><strong>Krüger, Grund, and Roth, 28 October 2024.</strong> <em>Inkonsistente Wahrnehmungen sozialer Unterstützungsbeziehungen in gleich- und gegengeschlechtlichen Dyaden.</em> 9th Congress of the German Society for Network Research, Schader Stiftung Darmstadt.</li> 
    <li><strong>Krüger, Grund, Tiernan, and Hellpap, 29 June 2024.</strong> <em>Harmony on the Plate: Peer Networks and the Evolution of Adolescent Vegetarian Practices.</em> Sunbelt Conference, Edinburgh.</li> <li><strong>Krüger, 26 October 2023.</strong> <em>The SOCIALBOND Project – Perspectives of a Student Survey for Health Research.</em> 8th Congress of the German Society for Network Research, University of Heidelberg.</li> 
    <li><strong>Krüger and Grund, 6 September 2023.</strong> <em>Dual perspectives in social support relationships.</em> 7th European Conference on Social Networks (EUSN 2023), University of Ljubljana.</li> 
    <li><strong>Krüger and Grund, 15 March 2023.</strong> <em>Dual perspectives in social support relationships.</em> Spring Conference of the DGS Section Sociological Network Research, Thünen Institute.</li> 
    <li><strong>Krüger, Kroneberg, and Kruse, 6 October 2022.</strong> <em>Mode of Contact with Friends and Mood Changes in German Adolescents during the COVID-19 Pandemic – An Ecological Momentary Assessment Study.</em> European Sociological Association (ESA) RN21 Midterm Conference 2022 on Quantitative Methods and the COVID-19 Pandemic, University of Salamanca.</li> 
    <li><strong>Krüger, 8 September 2022.</strong> <em>Everyday discrimination, social support, and mood changes in young immigrants in Germany.</em> European Association of Social Psychology (EASP) Meeting: The Role of Emotions in Interethnic Relations, Utrecht University.</li> 
    <li><strong>Krüger, Hasselhorn, and Sattler, 24 August 2021.</strong> <em>The conditional effects of stress on cognitive enhancement.</em> The Ethical, Legal, and Social Aspects of Cognitive Enhancement Strategies, University of Cologne and Bielefeld University.</li> 
    <li><strong>Krüger, 18 March 2021.</strong> <em>Co-Development of Social Isolation, Loneliness and Mental Health in Adolescence.</em> Spring Conference of the DGS Section Sociological Network Research, University of Wuppertal.</li> 
    <li><strong>Krüger, 13 July 2020.</strong> <em>Social Isolation, Perceived Loneliness and Mental Health in Adolescence.</em> Sunbelt Virtual Conference, Paris.</li> 
    <li><strong>Krüger, 6 February 2020.</strong> <em>Peer Support Networks and Personality Trait Development in Adolescence. A Social Network Analysis of Reciprocal Causation using RSiena.</em> Poster presentation, conference “How Networks Matter. Theoretical, Methodological and Empirical Advances on Network Mechanisms and Effects”, University of Bremen.</li>
  </ul>
</div>
