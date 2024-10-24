# Triggerbee Tracking Template for Google Tag Manager

The **Triggerbee Tracking Template** enables seamless integration of **Triggerbee** with **Google Tag Manager (GTM)**, allowing you to track visitor interactions, personalize experiences, and measure conversions across your website. 

This template simplifies the process of injecting Triggerbee’s tracking scripts into your website, helping you monitor key actions, track conversions, and push data to the Google Tag Manager **DataLayer** for further analysis and reporting.

## Features

- **Track Visitor Interactions**: Capture detailed visitor behavior and track goals or conversions.
- **Personalize Experiences**: Dynamically adjust content or trigger actions based on visitor behavior.
- **Easy DataLayer Integration**: Push Triggerbee event data (e.g., `triggerbeeActive`) directly to the GTM **DataLayer**.

## Requirements

- **Google Tag Manager** account
- **Triggerbee** account
- Website with **Google Tag Manager** installed

## Installation

### Step 1:  Install and configure the Template

1. In GTM, create a new **Tag** and find the **Triggerbee Tracking Template** by searching the community templates.
2. Fill in your **Triggerbee Site ID** (found in your Triggerbee account).
3. Optionally, enable **DataLayer push** for tracking successful Triggerbee events.

### Step 3: Add Triggers

1. Assign a **Trigger** to the **Triggerbee Tracking Tag** to determine when the tag should fire (e.g., on **Page View** or **Custom Events**).
2. Click **Save**.

### Step 4: Publish

1. After setting up your tags and triggers, **Preview** the container to test your setup.
2. Once tested, click **Submit** to publish your changes.

## Usage

Once installed and configured, the Triggerbee tracking script will be injected onto your site, allowing you to monitor visitor interactions and conversions via **Google Tag Manager**.

If **DataLayer push** is enabled, the event **`triggerbeeActive`** will be pushed to the GTM **DataLayer**, where you can set up additional tags or triggers based on the event.
