# Chrome Web Store

Developer Dashboard fields

## Description

A few years after regulators passed laws like GDPR and CCPA to protect the privacy of consumers, the sites have found ways to overcome these limitations by turning the Web into a labyrinth of options that usually make the user click on "Accept all" and forget about how their data is managed.

Global Privacy Control (GPC) is the solution for it. Together, many organizations are developing a specification to make your browser do that for you and tell the websites that you don't want to get tracked.

This extension enables GPC, so every site that implements it will not bother you anymore. So far only a limited set of ~1000 websites like The NY Times or DuckDuckGo implement this feature, but it is a matter of time that this specification grows and becomes an standard.

Let's fix the Web together.

You can check if you have GPC enabled at: https://global-privacy-control.glitch.me/

## Category

Productivity

## Language

English (United States)

## Store icon

![logo.svg]

## Screenshots

![screenshot.png]

## Single purpose description

Enable Global Privacy Control on Google Chrome.

## webRequest justification

Set the Set-GPC header.

## webRequestBlocking justification

Make the Set-GPC header be available before the server consumes it.

## Host permission justification

Make GPC be enabled in every site.