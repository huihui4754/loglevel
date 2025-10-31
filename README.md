# loglevel
简单的打印库,不依赖额外的库, 使用 print 和 printf 实现。加入了 level 等级控制打印是否输出，和打印时输出所在代码文件名

````go

package main

import (
	"github.com/huihui4754/loglevel"
)

func main() {
    logger  = loglevel.NewLog(loglevel.Info)
    logger.Debug("hello")

    //  logger.Debug(msgArr ...any)
    //  logger.Debugf(format string, msgArr ...any)
    //  logger.Error(msgArr ...any)
    //  logger.Errorf(format string, msgArr ...any)
    //  logger.Info(msgArr ...any)
    //  logger.Infof(format string, msgArr ...any)
    //  logger.Warn(msgArr ...any)
    //  logger.Warnf(format string, msgArr ...any)

}

````