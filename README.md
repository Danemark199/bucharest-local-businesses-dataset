# Bucharest Local Businesses & Restaurants Dataset (AI-Filtered)

An open-source JSON dataset containing aggregated, publicly available factual data about local businesses (restaurants, dentists, medical clinics, and services) in Bucharest, Romania. 

## 🎯 About the Project

This dataset was compiled during the backend development and data engineering phase of **[CautaAcum.ro](https://cautaacum.ro)** — an AI-powered local directory for Bucharest. 

The local search ecosystem is heavily polluted with fake ratings. To solve this, we aggregated geographical data for thousands of places in Bucharest and processed their user feedback through an LLM to generate honest, unbiased summaries. 

This repository shares the raw geographical and rating baseline data (strictly factual, excluding proprietary review texts) for educational purposes, data science projects, and local market analysis in Romania.

To see the live implementation of this data with full AI-generated insights, visit the **[Bucharest AI Business Directory](https://cautaacum.ro)**.

## 📊 Data Structure

The dataset is provided in a lightweight `JSON` format. Each entry includes coordinates, categories, and raw rating metrics:

```json
{
      "place_id": "g_0x40b202083d0f66af:0x62072d96d26",
      "name": "ZenSushi",
      "lat": 44.4618163,
      "lng": 26.0964098,
      "rating": 4.7,
      "reviews_count": 2262,
      "sector": null,
      "neighborhood": null,
      "city": "Bucuresti",
      "last_seen_at": "2026-02-04T10:14:39.000Z",
      "ai_verdict": "Recenziile descriu în general o experiență foarte bună, cu accent pe pește proaspăt, ingrediente de calitate și preparate japoneze autentice (sushi, ramen, tartar), prezentate atent. Mulți clienți laudă și amabilitatea personalului, precum și servirea rapidă, iar meniul este perceput ca variat, cu opțiuni speciale și deserturi apreciate.\n\nExistă însă și opinii mai rezervate: unii au considerat că mâncarea nu a fost memorabilă (în special ramenul, comparat nefavorabil cu alte locuri), iar terasa încălzită și anumite aspecte de organizare/servire ar avea loc de îmbunătățiri. Per ansamblu, este văzut ca o opțiune solidă pentru restaurant dorobanti bucuresti, inclusiv pentru cei care caută restaurant japonez bucuresti dorobanti sau restaurant japonez bucuresti floreasca.",
      "categories": [
        {
          "slug": "restaurant",
          "name_ro": "Restaurant"
        }
      ]
    }
