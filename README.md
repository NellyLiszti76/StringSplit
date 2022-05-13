# StringSplit
$loginButton = _IEGetObjById($oIE, "btnLogin") Sleep(100) _IEAction($loginButton, "click")  _IELoadWait($oIE)  _IEAttach(_IEPropertyGet($oIE, "locationurl"),"url")   Sleep(10000)  $dtfinal = _IEGetObjById($oIE, "txtDtFim") $datahoje = StringSplit(_NowDate(),"/") Sleep(100) _IEAction($dtfinal, "focus")
