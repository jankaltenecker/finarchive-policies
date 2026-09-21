# Privacy Policy

**Application:** FinArchive
**Last updated:** 2026-09-22

## In one paragraph

FinArchive is a personal application with a single user. That user is also its
author, the owner of every account it reads, and the only person whose personal
data it processes. It exists to keep a private, accurate record of its author's
own financial history. It has no customers, no sign-up, no analytics and no
third-party sharing.

## Who is responsible

The author of the application is both the data controller and the only data
subject. There is no organisation behind it and no second party with access.

Enquiries can be sent to the data protection address registered with the
open-banking provider for this application.

## What data is processed

Only data belonging to accounts the author has personally and explicitly linked:

- account identifiers, names, currencies and balances
- transaction records — dates, amounts, and the counterparty details the
  institution itself supplies, which include the other party's name and, where
  the institution states it, their account identifier
- documents the institution makes available to its own account holder, such as
  statements and settlement notes

No personal data is gathered about anyone from any source other than the
author's own bank statements. Where another party's name or account identifier
appears, it is present only because the institution wrote it into the record of
the author's own account, as every bank statement has always done. It is not
enriched, looked up, cross-referenced, or combined with anything else, and it is
used for one purpose: recognising which of the author's own accounts a transfer
went to, and telling one payment apart from another.

A great many of those counterparties are the author's own other accounts. The
rest are the shops, employers, insurers and public bodies that appear on any
current account.

## Where the data goes

Into a PostgreSQL database running on hardware the author owns and controls.

It is **not** sent to any cloud service, analytics provider, advertising
network, machine-learning training process, or any other third party. It is not
sold, shared, published, or made available to anyone. There is no telemetry.

## Who else is involved

Reading a payment account under PSD2 requires a licensed Account Information
Service Provider. FinArchive uses **Enable Banking Oy**, a provider licensed and
supervised by the Finnish Financial Supervisory Authority, which transmits
account data from the institution to the application at the author's request and
under the author's explicit consent.

Some institutions are read through their own published interfaces instead, in
which case no third party is involved at all.

## Legal basis and consent

Processing rests on the author's own consent, granted separately for each
institution through that institution's own authentication, and on the author's
legitimate interest in keeping records of their own finances.

Consent is granted per institution, is limited to the accounts explicitly
linked, and expires automatically — under PSD2 this is at most 180 days, after
which it must be granted again. It can be withdrawn at any time, either in the
application or directly at the institution, and withdrawal stops all further
access immediately.

## Access requested

Read access only. The application requests account information; it does not
initiate payments, place orders, or modify anything at any institution. Where an
institution offers no read-only credential, the application refuses write
requests itself before they are sent.

## Retention

Records are kept for as long as the author wishes to keep them, which is the
point of the application. As the only data subject, the author can inspect,
export, correct or delete any of it at any time, without asking anyone.

## Your rights

If you are reading this and are not the author, the only way this application
could hold anything about you is that you sent the author money or were sent
money by them, in which case it holds what their own bank statement says about
that payment — the same record their bank has kept regardless. Nothing is
gathered about you from anywhere else, and nothing is shared with anyone.

If you want to know what that record contains, or want it erased, use the
contact route above.

## Changes

This document is versioned in public at
<https://github.com/jankaltenecker/finarchive-policies>. Its history is the
change log.
