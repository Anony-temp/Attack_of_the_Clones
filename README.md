# Attack of the Clones

## Title

## Authors

## Abstract

# Overview

# Build Environment

# Prerequisites

# \[Venue\] Evaluation

## To Reproduce the throught measurement in Section 3

1. To make commit raw value, call the `generate_maintenance_raw_data` in `main_maintenance.py` file.
   - The function can be executed in parallel. Please, change `idx` value when the function is parallelly executed.

2. If the `generate_maintenance_raw_data` function is unusually finished due to some errors, you can check the errors with `lack_of` function in `main_maintenance.py` file.

3. To make maintainability value, call the `maintenance_value` in `main_maintenance.py` file.
   - You can adjust time interval with two values in `obtain_maintenance_value(start date, end date)`. The format of date is YYYYMMDD.
   - You can obtain maintainability value of one target coin. For example, if you want to obtain the value of Bitcoin, please input like `parsing("BTC", False, output filename)`.
   - You can obtain maintainability value of all coins. For example, we input like `parsing(None, True, output filename)`.

4. To cluster the maintainability values, call the `kmeans` in `main_maintenance.py` file.
