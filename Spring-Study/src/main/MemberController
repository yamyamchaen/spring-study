package hello.hellospring.controller;

import hello.hellospring.service.MemberService;
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.stereotype.Controller;
import org.springframework.web.bind.annotation.GetMapping;

@Controller
public class MemberController {

    private final MemberService memberService;

    @Autowired    
    public MemberController(MemberService memberService) {

        this.memberService = memberService;
    }

/*
회원 등록 폼 컨트롤러 추가
*/
    @GetMapping("/members/new")
    public String createHome() {
        return "members/createMemberForm";
    }
}
출처: https://cs-kookmin-club.tistory.com/671 [KMU_SW_CLUB:티스토리]
