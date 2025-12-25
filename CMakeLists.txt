cmake_minimum_required(VERSION 4.0)
project(OrderBook)

set(CMAKE_CXX_STANDARD 20)

add_executable(OrderBook main.cpp
        Usings.h
        TradeInfo.h
        Trade.h
        Side.h
        OrderbookLevelInfos.h
        Orderbook.h
        OrderType.h
        OrderModify.h
        Order.h
        LevelInfo.h
        Orderbook.cpp
        Constants.h)