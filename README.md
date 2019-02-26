# logback
logback日志配置说明
when it is used,you shuould :

import org.slf4j.Logger;

//Class like class User:User.class

Logger logger= LoggerFactory.getLogger(Class.class);
logger.debug(msg);
logger.info(msg);
logger.error(msg);
