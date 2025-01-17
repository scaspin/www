---
layout: project
title: "SVE: Distributed Video Processing at Facebook Scale"
project_id: sve
---

Videos are an increasingly utilized part of the experience of the billions of
people that use Facebook. These videos must be uploaded and processed before
they can be shared and downloaded. Uploading and processing videos at our
scale, and across our many applications, brings three key requirements: low
latency to support interactive applications; a flexible programming model for
application developers that is simple to program, enables efficient processing,
and improves reliability; and robustness to faults and overload. This paper
describes the evolution from our initial monolithic encoding script (MES)
system to our current Streaming Video Engine (SVE) that overcomes each of the
challenges. SVE has been in production since the fall of 2015, provides lower
latency than MES, supports many diverse video applications, and has proven to
be reliable despite faults and overload.
