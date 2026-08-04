---
title: "Rama in five minutes (Clojure version)"
url: "https://blog.redplanetlabs.com/2025/12/02/rama-in-five-minutes-clojure-version/?utm_source=rss&utm_medium=rss&utm_campaign=rama-in-five-minutes-clojure-version"
date: "2025-12-02"
author: "Nathan Marz"
feed_url: "https://blog.redplanetlabs.com/feed/"
---
Building with a traditional Postgres stack You start with two tables and an index on user_id . 1234567891011121314CREATE TABLE todos ( id SERIAL PRIMARY KEY, user_id BIGINT NOT NULL, text TEXT NOT NULL, completed_at TIMESTAMPTZ ); CREATE INDEX ON todos(user_id); CREATE TABLE todo_stats ( user_id BIGINT PRIMARY KEY, completed_count … Continue reading Rama in five minutes (Clojure version)
