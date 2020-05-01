local part = workspace.CameraPart 
repeat wait() until game:service("ContentProvider").RequestQueueSize == 0

local cam = workspace.CurrentCamera
cam.CameraSubject = part 
cam.CameraType = Enum.CameraType.Track 
