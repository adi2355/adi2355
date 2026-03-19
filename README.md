<p align="center">
    <img src="./banner-2x.gif" alt="Aditya profile banner" align=center width="75%" />
</p>


# Aditya Khetarpal

Reliable edge-to-cloud systems engineer building connected-device platforms across firmware, native mobile, sync infrastructure, and personalized intelligence.

I work across the full system boundary: dual-core RTOS firmware, binary BLE transport, native iOS and Android runtimes, offline-first local data layers, backend sync and worker infrastructure, and intelligence systems grounded in real device and health context.

My focus is production-grade software that remains correct, observable, and recoverable under real-world constraints: partial failure, retries, stale state, background execution limits, power interruption, and long-lived distributed workflows.

## What I build

### Edge firmware
Dual-core RTOS firmware for connected devices, with clear separation between timing-sensitive paths and background work. This includes BLE protocol transport, OTA delivery and rollback, deep sleep and wake handling, calibration under noisy physical conditions, and constrained on-device inference.

### Native mobile systems
Native iOS and Android runtimes for BLE connectivity, restoration, reconnection, and background-safe device communication. I design mobile architectures that stay coherent under intermittent networks, large health backfills, interrupted sessions, and lifecycle-driven execution limits.

### Data reliability and sync
Offline-first data systems built around local state as a durable interaction layer. My work here includes SQLite-first UX, transactional outbox patterns, cursor-based sync, tombstones, ID mapping, and reconciliation paths that remain safe under retries, duplicates, partial success, and long offline windows.

### Cloud and worker infrastructure
Backend APIs, queue-backed workers, realtime delivery, and bounded processing pipelines designed for correctness under failure. I care about idempotency, explicit latency budgets, observability, controlled fan-out, and systems that degrade deliberately rather than fail invisibly.

### Intelligence and personalization
TinyML and personalization systems built as product infrastructure rather than model wrappers. This includes structured longitudinal memory, retrieval across comparable user states, and tool-enabled intelligence grounded in trusted data paths, explicit controls, and interpretable fallback behavior.

## Selected projects

- **[ESP32-S3 Edge Firmware Platform](#)**  
  Dual-core FreeRTOS firmware with binary BLE transport, OTA recovery, deep sleep, calibration logic, and on-device intelligence.

- **[Offline-First Mobile Device Platform](#)**  
  Native BLE runtime, health ingestion pipelines, SQLite-first UX, and transactional sync architecture.

- **[Device Cloud & Sync Backend](#)**  
  Queue-backed workers, realtime delivery, cursor sync, conflict resolution, telemetry, and reliability-focused backend services.

- **[TinyML Sensor Intelligence Lab](#)**  
  Dataset logging, baseline-vs-model evaluation, on-device inference, and personalization on constrained hardware.

## Built for production reality

I’m interested in systems that hold up outside the happy path: retries, duplicates, reordering, stale caches, torn writes, queue backlogs, reconnect storms, mixed-version rollouts, and partial infrastructure failure. The goal is not just shipping features, but building systems that are explicit in state, bounded in work, and recoverable when distributed reality shows up.

## Areas I work across

`Multithreading / Microcontrollers / FreeRTOS` `BLE / NimBLE / Binary Protocols` `Swift / Kotlin` `React / React Native / TypeScript` `SQLite / Offline-First Architecture` `Transactional Outbox / Cursor-Based Sync` `PostgreSQL / Prisma / Redis` `BullMQ / WebSockets / Realtime Systems` `HealthKit / Health Data Pipelines` `OTA / Low-Power Embedded Systems` `TinyML / Edge AI` `Hybrid AI / Personalization / Predictive Analytics`
