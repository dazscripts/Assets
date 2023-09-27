# Roblox Recording Module
    
## Description:
*This module allows for recording and playback of player movements and animations.*
    
### Features:

    1. Start and stop recording
    2. Play recordings
    3. Support for multiple recordings
    4. Save and load recordings
    5. Metadata and time markers
    6. Audio support (mocked)
    7. Optimization settings
    8. Speed control
    9. Batch operations
    10. Statistics
    11. Playback settings
    
### Methods:
    1. StartRecording(metaData)
    2. StopRecording()
    3. PlayRecording(sessionId)
    4. SaveRecording(sessionId)
    5. LoadRecording(sessionId, encodedData)
    6. AddTimeMarker(markerName)
    7. BatchPlay(sessionIds)
    8. BatchDelete(sessionIds)
    9. BatchSave(sessionIds)
    10. GetStats(sessionId)
    
### Settings:
    1. fps: Frame rate for recording
    2. timeLimit: Maximum time for recording
    3. playbackSpeed: Speed for playback
    4. skipToTimestamp: Timestamp to start playback
    5. recordAnimations: Whether to record animations
    6. filterPlayers: Array of UserIds to specifically record
    7. filterParts: Array of part names to specifically record
    8. recordAudio: Whether to mock audio recording (actual audio recording not supported)
    9. optimization: Settings for optimizing recording performance
    10. playback: Additional settings for controlling playback experience
