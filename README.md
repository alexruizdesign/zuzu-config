# zuzu-config

Remote parse rules and announcements for ZUZU Stream. Served by GitHub Pages.

The app only accepts `rules.json` when `rules.json.sig` verifies against the
public key compiled into the app. Edit, then sign before pushing:

    swift ~/Xcode/ZUZUStream/Tools/sign-rules.swift sign rules.json

Rules can only sort and hide what the UZZU feed already contains. Never put a
URL or host in this file.
