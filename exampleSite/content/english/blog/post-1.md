---
title: Project Documentation
author: John Doe
date: '2025-02-03'
version: '1.0'
config:
  theme:
    darkMode: true
    colors:
      primary: '#592c22'
      secondary: '#274049'
      background: '#6b2929'
  layout:
    header:
      enabled: true
      style:
        backgroundColor: '#333333'
        fontSize: 16px
    footer:
      enabled: true
      content:
        text: 2025 - All rights reserved
        links:
          - label: Privacy Policy
            url: /privacy-policy
          - label: Terms of Service
            url: /terms
  features:
    authentication:
      enabled: true
      providers:
        google: false
        github: true
    dashboard:
      widgets:
        - type: charts
          enabled: true
        - type: tasks
          enabled: false
draft: false
---
# Project Documentation

## Overview

This document provides detailed information about the project's structure, including configurations, settings, and more.

## Schema

```json
{
  "user": {
    "name": "John Doe",
    "contact": {
      "email": "john.doe@example.com",
      "phone": "+123456789"
    },
    "preferences": {
      "notifications": {
        "email": true,
        "sms": false
      },
      "theme": "dark"
    },
    "address": {
      "street": "123 Main St",
      "city": "New York",
      "state": "NY",
      "postalCode": "10001",
      "country": "USA"
    }
  }
}
```
