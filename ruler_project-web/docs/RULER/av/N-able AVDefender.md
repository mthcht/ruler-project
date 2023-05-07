# N-Able AV Defender

## Event Logs

Unknown

## Application specific files

* \Program Files (x86)\N-able Technologies\Windows Agent\log\AVDefenderSecurityEvents.log
    - Line format:
        - [GeneralEventsDataCollector] 2021-10-28 04:36:24,762 WARN  com.nable.agent.AVDefenderMaintenance.GeneralEventsDataSubmit Event message: <JSON DATA>
* <uknown start>\N-Able Technologies\AVDefender\Logs
* \Program Files (x86)\N-able Technologies\Tools\log\EndPointSDK.log

## Quarantine

* \Program Files\N-able Technologies\AVDefender\Quarantine\cache.db\
    - table: entries
    - fields: Quarid, path, threat, status, size, quartime, acctime, modtime, scanflags, usersid
    - notes: timestamps are unix timestamps