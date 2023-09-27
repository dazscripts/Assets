# Roblox Recording Module
    
## Description:
> This module allows for recording and playback of player movements and animations.
    
### Features:
> Start and stop recording

> Play recordings

> Support for multiple recordings

> Save and load recordings

> Metadata and time markers

> Audio support (mocked)

> Optimization settings

> Speed control

> Batch operations

> Statistics

> Playback settings
    
### Methods:
    - StartRecording(metaData)
    - StopRecording()
    - PlayRecording(sessionId)
    - SaveRecording(sessionId)
    - LoadRecording(sessionId, encodedData)
    - AddTimeMarker(markerName)
    - BatchPlay(sessionIds)
    - BatchDelete(sessionIds)
    - BatchSave(sessionIds)
    - GetStats(sessionId)
    
### Settings:
    - fps: Frame rate for recording
    - timeLimit: Maximum time for recording
    - playbackSpeed: Speed for playback
    - skipToTimestamp: Timestamp to start playback
    - recordAnimations: Whether to record animations
    - filterPlayers: Array of UserIds to specifically record
    - filterParts: Array of part names to specifically record
    - recordAudio: Whether to mock audio recording (actual audio recording not supported)
    - optimization: Settings for optimizing recording performance
    - playback: Additional settings for controlling playback experience
