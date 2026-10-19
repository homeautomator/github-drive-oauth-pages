# GitHub Drive Automation

A personal-use application that enables GitHub Actions workflows to securely access Google Drive using OAuth 2.0.

## Purpose

This application allows automated Python scripts running through GitHub Actions to:

- Read authorised files from Google Drive.
- Create new files in designated Google Drive folders.
- Update existing files.
- Process and export data automatically.
- Run scheduled workflows without requiring repeated manual sign-in.

## Authentication and Security

- Authentication uses Google OAuth 2.0.
- Access is authorised by the Google account owner.
- OAuth credentials and refresh tokens are stored securely in GitHub Actions secrets.
- Google Drive permissions are limited to the scopes granted by the account owner.
- The application is intended for personal use and is not offered as a public service.

## Privacy

Google Drive data is accessed solely for the account owner's authorised automation workflows.

For further information, see the [Privacy Policy](privacy.md).

## Access

This repository hosts public information about the OAuth application.

It does not contain Google Drive files, OAuth credentials, access tokens or refresh tokens.

The application's automation scripts are maintained separately.
