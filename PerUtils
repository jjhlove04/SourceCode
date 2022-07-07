using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public static class PerUtils
{
    public static bool ReturnPercent(float percent)
    {
        //수가 너무 작을시 값 고정
        if(percent < 0.1f)
        {
            percent = 0.1f;
        }
      
        //확률계산시 필요한 백분률 표시
        percent = percent / 100;
        bool result = false;
        int arrCount = 100;
        float randomHit = percent * arrCount;
        int random = UnityEngine.Random.Range(1, arrCount + 1);
        if(random <= randomHit)
        {
            result = true;
        }
        
        return result;
    }
}
