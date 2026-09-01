package log

import (
	"github.com/fatedier/golib/log"
)

// InitLog initializes logger with specified target, level, and retention settings.
func InitLog(logWay, logFile, logLevel string, maxDays int64, disableLogColor bool) {
	log.InitLog(logWay, logFile, logLevel, maxDays, disableLogColor)
}